# ♟️ Real-Time Chess Game

![HTML5](https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-lightgreen?logo=node.js&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-black?logo=socket.io&logoColor=white)
![Open Source](https://img.shields.io/badge/Open%20Source-💻-brightgreen)
![Made with ❤️ by Aniket](https://img.shields.io/badge/Made%20with-❤️-red)

> ♟️ A **real-time multiplayer chess game** where two players can play live using **Socket.IO** for real-time communication and a **Chess API** to handle game logic.

---

## 🚀 **Overview**

This project is a **full-stack real-time chess game** with the following features:  

- 🔹 Two players can connect and play live  
- 🔹 Real-time board updates using **Socket.IO**  
- 🔹 Chess moves validated by **Chess API / chess.js**  
- 🔹 Visual chessboard rendered with **HTML/CSS/JS**  
- 🔹 Move history and turn management  

It’s perfect for practicing **WebSockets, real-time multiplayer logic, and frontend-backend integration**.

---

## 🧰 **Tech Stack**

| Tech | Description |
|------|-------------|
| 🟢 Node.js | Backend server |
| ⚙️ Express.js | Handles server routes |
| 🔌 Socket.IO | Real-time communication between clients |
| ♟️ Chess.js or Chess API | Chess game logic and validation |
| 🎨 HTML/CSS | Chessboard UI and styling |
| ⚡ JavaScript | Move handling, event listeners, and board updates |

---

## ⚙️ **Features**

- ✅ Two-player real-time chess  
- ✅ Move validation using Chess API / chess.js  
- ✅ Real-time updates with Socket.IO  
- ✅ Turn management and move history  
- ✅ Game over detection (checkmate, stalemate, draw)  

---

## ⚙️ **How It Works**

1. **Server Setup**  
   - Express server handles HTTP requests  
   - Socket.IO initialized for real-time events  
   - Each room corresponds to a single chess game  

2. **Connecting Players**  
   - Player 1 creates a room  
   - Player 2 joins the room via a room code  

3. **Game Play**  
   - Players make moves on the board  
   - Moves are validated using Chess API or chess.js  
   - Valid moves emitted via Socket.IO to the other player in real-time  

4. **Game State**  
   - Move history tracked  
   - Detect checkmate, stalemate, or draw  
   - Option to reset or start a new game  

---

## 💻 **Setup & Usage**

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/realtime-chess.git
cd realtime-chess
