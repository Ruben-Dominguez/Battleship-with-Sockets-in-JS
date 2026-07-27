# Battleship with Sockets in JS 🚢💥

PLAY HERE: https://battleship-ham1.onrender.com/

A real-time, multiplayer Battleship game built with JavaScript, Node.js, and WebSockets (Socket.io). 

Play the classic naval combat game against other players online in your browser. This project demonstrates real-time bidirectional communication between a client and a server.

## 🎮 Features

* **Real-time Multiplayer:** Play against another human player instantly using WebSockets.
* **Interactive UI:** Drag and drop your ships to position them on the grid.
* **Live Game State:** See instant feedback on hits, misses, and sunken ships.
* **Lobby/Matchmaking:** Wait for a second player to connect before the game begins.

## 🛠️ Technologies Used

* **Frontend:** HTML, CSS, Vanilla JavaScript
* **Backend:** Node.js, Express.js
* **Real-Time Communication:** [Socket.io](https://socket.io/)

## 📂 Project Structure

```text
├── public/              # Frontend assets (HTML, CSS, client-side JS)
├── server.js            # Node.js Express server and Socket.io setup
├── package.json         # Project metadata and dependencies
└── package-lock.json    # Dependency tree lockfile
