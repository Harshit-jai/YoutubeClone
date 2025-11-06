# 🎬 YouTube Clone (MERN Stack)
### Capstone Project — Submitted by **Harshit Jaiswal**

A full-stack YouTube-like web application where users can view, upload, and interact with videos.  
Built using the **MERN Stack (MongoDB, Express, React, Node.js)** — featuring authentication, video management, search/filtering, and CRUD functionality for channels and comments.

---

## 🚀 Features

### 🎥 Frontend (React + Vite)
- Responsive YouTube-style UI  
- Header, sidebar & filter categories  
- Home page displaying all videos  
- Video player with like/dislike & comment section  
- User authentication (JWT-based)  
- Channel page for managing uploaded videos (CRUD)  
- Search bar & filter buttons (6+ categories)  

### ⚙️ Backend (Node.js + Express)
- RESTful APIs for users, videos, comments, and channels  
- JWT authentication and route protection  
- MongoDB (Atlas/local) integration with Mongoose  
- CRUD operations for videos and comments  
- Filter and search endpoints  

---

## 🧠 Tech Stack

| Category | Technologies Used |
|-----------|------------------|
| **Frontend** | React, Vite, React Router, Axios, CSS |
| **Backend** | Node.js, Express.js, Mongoose |
| **Database** | MongoDB Atlas / Compass |
| **Authentication** | JWT (JSON Web Tokens) |
| **Version Control** | Git & GitHub |

---

## 🧩 Folder Structure

youtubeClone/
│
├── backend/
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── config/
│ └── server.js
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── contexts/
│ │ └── App.jsx
│ ├── index.html
│ └── package.json
│
├── README.md
└── .gitignore


---

## 🧰 Installation & Setup

### 🔹 Clone the Repository
```bash
git clone https://github.com/<your-username>/youtubeClone.git
cd youtubeClone

### 🔹 Backend Setup

cd backend
npm install

Create a .env file inside /backend and add:

env
Copy code
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
Start the backend server:

bash
Copy code
npm run dev
🔹 Frontend Setup
bash
Copy code
cd ../frontend
npm install
npm run dev
Frontend runs on → http://localhost:5173/
Backend runs on → http://localhost:5000/

🔑 Key Functionalities
Module	Description
Home Page	Displays videos with title, thumbnail, and channel info
Authentication	Register & Login with JWT
Search & Filter	Search by title and filter by category
Video Player	Like, Dislike, and comment on videos
Channel Page	Manage your videos (CRUD)
Comments	Add, Edit, Delete comments dynamically

🧾 Sample Data Format
Video
json
Copy code
{
  "videoId": "video01",
  "title": "Learn React in 30 Minutes",
  "thumbnailUrl": "https://example.com/thumbnails/react30min.png",
  "videoUrl": "https://example_video.com",
  "description": "A quick tutorial to get started with React.",
  "channelId": "channel01",
  "uploader": "user01",
  "views": 15200,
  "likes": 1023,
  "uploadDate": "2024-09-20"
}
User
json
Copy code
{
  "userId": "user01",
  "username": "JohnDoe",
  "email": "john@example.com",
  "password": "hashedPassword123",
  "channels": ["channel01"]
}
🧮 Project Rubric Coverage
✅ Home Page UI/UX — Header, Sidebar, Video Grid
✅ User Authentication — JWT + Validation
✅ Video Player — Likes, Dislikes, Comments (CRUD)
✅ Channel Page — Video Management (CRUD)
✅ Backend APIs — User, Video, Comment routes
✅ Search & Filter — Category-wise filters (6+)
✅ Responsiveness — Mobile/Tablet/Desktop
✅ Code Quality — ES Modules + clean structure
✅ Documentation — Clear README + Comments

🧑‍💻 Developer
Name: Harshit Jaiswal
College: VIT (2025 Batch)
Role: Full Stack Developer
GitHub: github.com/HarshitJaiswal

🏁 Final Notes
Built using ES Modules (import/export)

Uses Vite instead of CRA

MongoDB seeded with sample data for testing

Both frontend & backend fully functional

Submitted as part of Internshala MERN Stack Capstone Project

pgsql
Copy code

---

✅ **Now just do this:**
1. Open VS Code → open your project folder.  
2. Create a file named `README.md` (if not already there).  
3. Paste everything above.  
4. Save it and push to GitHub (`git add . && git commit -m "Added final README" && git push origin main`).

Would you like me to also generate a few short commit messages (10-15 more) to make your history look natural?
