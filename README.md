# 💬 Node.js Socket.IO Chat App

A real-time chat application built with **Node.js**, **Express**, and **Socket.IO**. Users can join the chat, send messages, and see who is online—all in real time!

---

## 🚀 Features

- Real-time messaging using WebSockets (Socket.IO)
- Displays online users
- Notifies when users join or leave the chat
- Simple and clean frontend (HTML/CSS/JS)
- No authentication required—just enter your name and chat!

---

## 🛠️ Tech Stack

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Socket.IO](https://socket.io/)

---

## 📁 Project Structure

```
Chat App/
│
├── public/
│   └── index.html        # Frontend for the chat app
├── server.js             # Main server file (Express + Socket.IO)
└── package.json          # Project dependencies and scripts
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd "Chat App"
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the server**
   ```bash
   npm start
   ```
   The server will run at [http://localhost:3000](http://localhost:3000).

4. **Open the app**
   - Visit [http://localhost:3000](http://localhost:3000) in your browser.
   - Enter your name when prompted and start chatting!

---

## 📝 Usage

- **Join the chat:** Enter your name in the prompt when the page loads.
- **Send messages:** Type your message and press "Send" or hit Enter.
- **See online users:** The sidebar lists all users currently online.
- **Notifications:** You'll see messages when users join or leave the chat.

---

## 📦 Scripts

- `npm start` — Starts the chat server (`server.js`).

---

## 🧩 How It Works

- The server ([server.js](server.js)) uses Express to serve static files and Socket.IO for real-time communication.
- When a user joins, their name is broadcast to all clients, and the user list is updated.
- Messages sent by any user are broadcast to all connected clients.
- When a user disconnects, all clients are notified and the user list updates.

---

## 🗂️ Key Files

- [`server.js`](server.js): Main server logic (Express + Socket.IO)
- [`public/index.html`](public/index.html): Frontend UI for the chat

---

## 🛡️ License

This project is licensed under the [ISC License](LICENSE).

---

## 🙋‍♂️ Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Contact

For questions or suggestions, open an issue or contact me.
