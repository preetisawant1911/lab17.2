# TaskMaster – MERN Deployment (Lab 2)

This project is a simple MERN (MongoDB, Express, React, Node.js) application deployed as part of Lab 2: Full‑Stack Deployment.  
The goal of this lab is to deploy both the backend and frontend to Render and connect them to a live MongoDB Atlas database.

---

## 🚀 Live Deployment Links

### 🔹 Backend (Render Web Service)  
https://your-backend-url.onrender.com

### 🔹 Frontend (Render Static Site)  
https://your-frontend-url.onrender.com

---

## 📌 Project Description

TaskMaster is a basic task management application built using the MERN stack.  
Users can create tasks and view them through a simple interface.  
This lab focuses on deployment rather than feature expansion.

---

## 🛠 Tech Stack

- **Frontend:** React  
- **Backend:** Node.js, Express  
- **Database:** MongoDB Atlas  
- **Hosting:** Render (Backend as Web Service, Frontend as Static Site)

---

## 💻 Frontend Setup (Local)

1. Navigate to the client folder:
   ```
   cd client
   ```
2. Install dependencies:
   ```
   npm install
   ```
3. Create a `.env` file:
   ```
   REACT_APP_API_URL=http://localhost:3001
   ```
4. Start the frontend:
   ```
   npm start
   ```

---

## ⚙️ Backend Setup (Local)

1. Navigate to the server folder:
   ```
   cd server
   ```
2. Install dependencies:
   ```
   npm install
   ```
3. Create a `.env` file:
   ```
   MONGODB_URI=your_mongodb_connection_string
   PORT=3001
   ```
4. Start the backend:
   ```
   npm start
   ```

---

## 🌐 Deployment Summary

### Backend (Render Web Service)
- Build Command: `npm install`
- Start Command: `npm start`
- Environment Variable: `MONGODB_URI`

### Frontend (Render Static Site)
- Build Command: `npm install && npm run build`
- Publish Directory: `build`
- Environment Variable:  
  ```
  REACT_APP_API_URL=https://your-backend-url.onrender.com
  ```

---

## ✔️ Lab Requirement Status

- Backend deployed ✔️  
- Frontend deployed ✔️  
- Both URLs publicly accessible ✔️  
- Frontend successfully communicates with backend ✔️  

---

## 👩‍💻 Author

**Preeti Sawant**  
GitHub: [https://github.com/preetisawant1911](https://github.com/preetisawant1911)

