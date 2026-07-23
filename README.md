# 💬 Real-time Chat Application

A full-stack real-time chat application built with **Haskell** and **React**, enabling multiple users to communicate instantly through WebSocket connections. The project demonstrates concurrent programming, RESTful API development, and real-time message processing.

---

## ✨ Features

- 🔹 Real-time messaging using WebSocket
- 🔹 Multiple client connections
- 🔹 User-friendly React interface
- 🔹 RESTful APIs with Servant
- 🔹 SQLite database integration
- 🔹 Concurrent message processing
- 🔹 Modular backend architecture

---

## 🛠 Tech Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3

### Backend
- Haskell
- Servant
- WebSocket

### Database
- SQLite
- Persistent

---

## 🏗 System Architecture

```text
React Client
      │
      │ WebSocket / HTTP
      ▼
Haskell Backend (Servant)
      │
      ▼
SQLite Database (Persistent)
```

---

## 📂 Project Structure

```text
Real-Time-Chat-App
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── app/
│   ├── src/
│   ├── config/
│   ├── Main.hs
│   └── package.yaml
│
├── images/
└── README.md
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/HuyVuCS/Real-Time-Chat-App.git
```

### Backend

```bash
cd backend

stack build

stack run
```

### Frontend

```bash
cd frontend

npm install

npm start
```

---

## 📌 Key Learning Outcomes

- Built a real-time communication system using WebSocket.
- Developed RESTful APIs with Servant.
- Applied concurrent programming techniques in Haskell.
- Managed persistent data storage with SQLite.
- Integrated a React frontend with a Haskell backend.
