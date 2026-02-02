# 📝 Task Manager Backend (Node.js & Express)

Backend service for a **Task Manager application**, built using  
**Node.js, Express.js, and MongoDB**.

This backend provides **RESTful APIs** for task management, user authentication, and secure data handling.

---

## 📌 Overview
The Task Manager Backend handles business logic, authentication, and database operations for managing user tasks in a secure and scalable way.

---

## 🚀 Features
- User authentication using JWT
- CRUD operations for tasks
- User-specific task management
- RESTful API architecture
- Secure password handling with bcrypt
- MongoDB integration using Mongoose
- Environment-based configuration

---

## 🛠️ Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Token (JWT)
- bcrypt
- dotenv

---

## 🔐 Authentication & Security
- JWT-based authentication using **jsonwebtoken**
- Protected routes for authorized users
- Password hashing using **bcrypt**
- Middleware-based access control

---

## 📂 API Endpoints (Overview)
- `/api/auth` → User authentication & registration
- `/api/tasks` → Task CRUD operations

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory:

env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

---
▶️ Run Locally
- npm install
- npm run start

---

🏗️ Architecture Overview

-Express handles routing and middleware

-MongoDB stores user and task data

-JWT secures API endpoints

-Designed to integrate with a React frontend

---

🔗 Frontend Repository

Frontend application is available here:
-https://github.com/Manfarisi/taskManager_frontend

---

👨‍💻 Author

-Salman Alfarisi
-GitHub: https://github.com/Manfarisi
