@@ -1 +1,80 @@
# realtime-chat-appilication
# realtime-chat-appilication
# 💬 Realtime Chat Application

A simple **Realtime Chat App** built using **Node.js**, **Express**, and **Socket.IO**.  
Users can chat instantly with each other in real time — no page refresh needed!

---

## 🚀 Features

- Realtime two-way communication using **Socket.IO**
- Instant message updates across all connected users
- Clean, responsive chat UI
- Lightweight and beginner-friendly setup

---

## 🧩 Project Structure

```
📁 realtime-chat-app/
├── 📁 public/
│   └── index.html        # Frontend (HTML, CSS, JS)
├── server.js             # Backend server (Express + Socket.IO)
└── package.json          # Dependencies and scripts
```

---

## ⚙️ Requirements

| Requirement | Description |
|--------------|-------------|
| **Node.js (v14 or higher)** | JavaScript runtime for backend |
| **npm (Node Package Manager)** | To install dependencies |
| **Web browser** | For testing the chat app |

---

## 📦 Installation

```bash
git clone https://github.com/your-username/realtime-chat-app.git
cd realtime-chat-app
npm install express socket.io
```

---

## 🖥️ Usage

```bash
node server.js
```

Then open in your browser:
```
http://localhost:3000
```

---

## 🧠 How It Works

- The server uses **Express** to serve frontend files.
- **Socket.IO** handles realtime, bidirectional communication.
- When a user sends a message, it’s broadcast to all connected clients instantly.

---

## 🧑‍💻 Author

**Your Name**  
GitHub: [@your-username](https://github.com/your-username)

---

## 📜 License

This project is licensed under the dharshan.d
