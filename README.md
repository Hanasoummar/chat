# 💬 Awal Chat App

> **Awal** (ⴰⵡⴰⵍ) — *"talks"* or *"speech"* in Tamazight, the Amazigh language of North Africa.

A real-time chat application built with Node.js and Socket.io, featuring named chat rooms and a custom dark-themed UI with pink and teal accents.

> 🧑‍💻 **Beginner project** — built in March 2023 by following the French tutorial series ["Créer un chat Socket.io en NodeJS"](https://www.youtube.com/watch?v=grE_gWwzNoU) by Antoine Drsl, then customized with my own branding and styling.

---

## ✨ Features

- 🚪 Create and join named chat rooms (e.g. `/room1`)
- ⚡ Real-time messaging powered by Socket.io
- 🔔 System notifications when a user joins a room
- 👥 Active users list dropdown
- 🖥️ Multi-tab support — test with multiple browser tabs
- 🎨 Custom "Awal" branding with a dark UI and pink/teal color scheme

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Runtime | Node.js |
| Framework | Express |
| Real-time | Socket.io |
| Templating | EJS |
| Frontend | HTML, CSS, Vanilla JS |

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Hanasoummar/chat.git
cd chat

# 2. Install dependencies
npm install

# 3. Start the server
node server.js

# 4. Open your browser
# Go to http://localhost:3000
```

---

## 📁 Project Structure

```
awal-chat-app/
├── server.js           # Main server — Express setup & Socket.io logic
├── views/
│   ├── index.ejs       # Landing page — enter a room name to join
│   └── room.ejs        # Chat room interface
├── public/
│   ├── script.js       # Frontend JavaScript (Socket.io client)
│   └── logo1.png       # Awal brand logo
├── package.json
└── package-lock.json
```

---

## 📸 Screenshots

**Landing Page** — Enter a room name and click "New Room"

![Landing Page](/public/landing.png)

**Chat Room** — Real-time messaging with join notifications

![Chat Room](/public/room.png)

**Multiple Users** — Multi-tab support in action

![Multiple Users](/public/multi-users.png)

---

## 📚 What I Learned

- Setting up a Node.js + Express server from scratch
- How WebSockets work and why Socket.io makes them easier
- Emitting and listening to events between server and client
- Managing multiple chat rooms and broadcasting to specific rooms
- Server-side rendering with EJS templates
- Organizing a basic full-stack project structure

---

## 🔮 Possible Future Improvements

- 🔐 User authentication (username/password or OAuth)
- 🗄️ Persistent message history with a database (MongoDB or PostgreSQL)
- 🕒 Message timestamps
- 🌐 Deployment to a live server (Railway, Render, etc.)
- 📱 Responsive mobile design
- 🔔 Browser notifications for new messages
- 🟢 Online/offline user status indicators
- 🔒 Private (direct) messaging between users

---

## 🙋 About Me

I am a Data Science enthusiast with a growing interest in web development, passionate about building end-to-end projects — from real-time applications to data pipelines and actionable insights.  
This project is part of my portfolio showcasing my learning journey across both software engineering and data-driven fields.

⭐ If you found this project useful, consider starring the repository — it helps others discover it too!

Built as a learning project — March 2023.

<p align="center">
  <sub>Built with ❤️ by <strong>Hana Soummar</strong> for learning and growth</sub>
</p>
