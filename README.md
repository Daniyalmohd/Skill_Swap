🔁 SkillSwap Hub — Learn & Teach Through Skill Exchange

SkillSwap Hub is a MERN stack web application where users can exchange skills instead of paying for courses. Users create profiles, list skills they can teach and want to learn, send swap requests, and chat in real-time once a request is accepted.

🚀 Features

🔐 User Authentication (JWT + bcrypt)

👤 Create Skill Profile (Teach / Learn skills)

🔎 Search Users by Skills

🤝 Send / Accept / Reject Swap Requests

💬 Real-Time Chat with Socket.io

⭐ Swap Completion & Reviews (optional)

🗂 Data stored in MongoDB

🛠 Tech Stack

Frontend

React 

Backend

Node.js

Express.js

Database

MongoDB + Mongoose

Authentication

JWT (jsonwebtoken)

bcryptjs

Real-Time

Socket.io

Utilities

cors, dotenv, concurrently

🧠 Application Flow

User signs up / logs in

Creates skill profile (skills to teach & learn)

Searches for users by skill

Sends swap request

Receiver accepts/rejects

If accepted → real-time chat starts

Users complete the skill swap

📡 Architecture
Frontend (React)
      │
      ▼
Backend API (Express)
      │
      ▼
MongoDB

Chat: Frontend ↔ Socket.io ↔ Frontend
