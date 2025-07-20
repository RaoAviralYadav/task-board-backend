# 🛠️ Task Board Backend – Real-Time Collaborative Kanban API

This is the **backend server** for the [Real-Time Collaborative Kanban Board](https://task-board-git-main-raoaviralyadavs-projects.vercel.app) – a Trello-inspired task management app that supports live updates, smart assignments, conflict handling, and user authentication.

<br/>

> 🌐 **Frontend Live App**: [Click Here](https://task-board-git-main-raoaviralyadavs-projects.vercel.app)  
> 🛠️ **API Base URL**: [https://task-board-backend-wbvr.onrender.com](https://task-board-backend-wbvr.onrender.com) 

---

## 📌 Key Features

- 🔐 **JWT-based Authentication** – Secure login and signup endpoints  
- 🧠 **Smart Task Assignment** – Assigns tasks to user with fewest active tasks  
- ⚔️ **Conflict Handling Logic** – Detects and resolves simultaneous edits  
- 💬 **Socket.IO Integration** – Real-time updates via WebSockets  
- 🗂️ **Activity Logs** – Track task edit history  
- ✅ **Validations** – Enforce task uniqueness and prevent title conflicts  

---

## 🧰 Tech Stack

- **Node.js + Express.js** – API Server
- **MongoDB + Mongoose** – Database & ODM
- **Socket.IO** – Real-time communication
- **JWT + bcrypt** – Auth & password security
- **CORS & dotenv** – Config & cross-origin support

---

## 📂 Project Structure

