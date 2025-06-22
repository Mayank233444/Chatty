# 💬 Chatty - Real-Time Chat Application

A sleek and modern real-time chat application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). Includes **authentication**, **group chats**, **live messaging**, and a beautiful UI powered by **Chakra UI**.

---



## 🚀 Live Demo

[Click here to view the deployed app 🔗](https://chatty-8e6a.onrender.com/)

---

## 🧠 Features

- 🔐 User registration & login with JWT-based authentication
- 👤 Profile view and update
- 🔍 Search users to start conversations
- 💬 One-to-one chat functionality
- 👥 Create, rename, and manage group chats
- 🔔 Real-time notifications using Socket.io
- 🌙 Clean and responsive Chakra UI interface

---

## 🛠️ Tech Stack

**Frontend**
- React.js
- Chakra UI
- Axios

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.io
- JWT (JSON Web Tokens)
- bcrypt.js

---

## 📦 Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/Mayank233444/Chatty.git
cd chatty
```
2. **Install Dependencies**

```bash
# Backend
npm install

# Frontend
cd ../frontend
npm install
```
3. **Environment Variables**
- Create a .env file inside the /backend folder with the following:
```bash
PORT=5000
MONGO_URI=your_mongo_connection_uri
JWT_SECRET=your_jwt_secret_key
NODE_VERSION=18.16.1
```
4. **Running the App Locally**

```bash
# Start the server
npm run start

# Start frontend
cd ../frontend
npm start

```
**Made By**
- Mayank
