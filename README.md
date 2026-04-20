#  WeCode

<p align="center">
  <b>Stop Solving Alone. Start Solving Together.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-13+-black?logo=next.js" />
  <img src="https://img.shields.io/badge/TypeScript-Strict-blue?logo=typescript" />
  <img src="https://img.shields.io/badge/Socket.io-Realtime-green?logo=socket.io" />
  <img src="https://img.shields.io/badge/Express.js-Backend-lightgrey?logo=express" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

---

## 🌐 Live Demo

🔗 **Frontend:** https://we-code-dsa.vercel.app  
🔗 **Backend API:** https://wecode-6hfa.onrender.com  

---

## Overview

WeCode is a real-time collaborative coding platform designed for :

- DSA Practice  
- Pair Programming  
- Interview Preparation  
- Brainstorming Coding Approaches  

Users can join shared rooms to:
- Write code together
- Chat in real-time
- Use a collaborative whiteboard
- Execute code in multiple languages instantly

---

## Core Features

-  Real-time collaborative code editor
-  Room-based session management
-  Live presence indicators
-  Integrated real-time chat
-  Shared whiteboard
-  Multi-language execution  (C++ , Java , Python , JavaScript)
-  Fully responsive UI

---

## Tech Stack

### Frontend
- Next.js (App Router)
- TypeScript
- Tailwind CSS
- Socket.io Client
- Monaco Editor

### Backend
- Node.js
- Express.js
- Socket.io
- In-memory Room State Management

### Code Execution
- Judge0 Community Edition API

---

## 🏗 Architecture

```

Client (Next.js)
↓
Socket.io Client
↓
Node + Express Server
↓
Room State (In-Memory)
↓
Judge0 API (Code Execution)

````

- WebSocket-based real-time synchronization
- Room isolation using Socket.io rooms
- State cleanup on disconnect
- Secure CORS configuration

---

## Run Locally

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/wecode.git
cd wecode
````

---

### 2️⃣ Backend Setup

```bash
cd server
npm install
npm run dev
```

Runs on:
👉 [http://localhost:5000](http://localhost:5000)

---

### 3️⃣ Frontend Setup

```bash
cd client
npm install
npm run dev
```

Runs on:
👉 [http://localhost:3000](http://localhost:3000)

---

## 🌍 Deployment

### Backend (Render)

* Root Directory: `server`
* Build Command:

  ```
  npm install && npm run build
  ```
* Start Command:

  ```
  npm start
  ```

### Frontend (Vercel)

* Root Directory: `client`
* Framework: Next.js

---

## Project Structure

```
WeCode/
├── client/        # Next.js frontend
├── server/        # Node.js backend
└── README.md
```

---

## 📸 Screenshots

*Add actual screenshots here for maximum impact*

```
/screenshots/editor.png
/screenshots/chat.png
/screenshots/whiteboard.png
```

---

## Current Limitations

* Room state stored in memory (resets on server restart)
* No authentication yet
* No persistent session history

---

## Future Improvements

* Authentication (JWT / OAuth)
* Redis for scalable room storage
* Custom test case execution system
* Session history & analytics
* Multi-instance horizontal scaling

---

## 📄 License

MIT License

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create your feature branch
3. Commit changes
4. Open a pull request

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 📢 Share it

---

