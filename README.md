# ♟️ Node Chess

A real time multiplayer Chess application built using **Node.js**, **Express.js**, **Socket.IO**, and **EJS**. The application allows two players to play chess in real time while spectators can watch the game live. Moves are synchronized instantly across connected clients, providing a smooth multiplayer experience.

---

## ✨ Features

- Real time multiplayer gameplay
- Live move synchronization using Socket.IO
- Automatic player assignment (White & Black)
- Spectator mode
- Instant board updates
- Legal move validation using Chess.js
- Responsive chessboard interface
- Fast and lightweight Node.js backend

---

## 🛠️ Tech Stack

### Backend
- Node.js
- Express.js
- Socket.IO

### Frontend
- EJS
- CSS
- JavaScript

### Libraries
- Chess.js

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/node-chess.git
```

Navigate to the project

```bash
cd node-chess
```

Install dependencies

```bash
npm install
```

Start the server

```bash
npm start
```

or

```bash
node app.js
```

Open your browser

```
http://localhost:3000
```

---

## 🎮 How It Works

- The first connected player becomes **White**.
- The second connected player becomes **Black**.
- Any additional users join as **Spectators**.
- Players make moves on the board.
- Every valid move is instantly broadcast to all connected clients using Socket.IO.
- Chess.js validates all legal moves and game state.

---

## Connect

If you found this project helpful, feel free to ⭐ the repository.