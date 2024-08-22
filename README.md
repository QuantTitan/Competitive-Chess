# Real-Time Multiplayer Chess Game

This is a real-time multiplayer chess game developed using a server-client architecture with JavaScript and Socket.io. The game allows players to connect, play chess in real time, and enjoy a seamless gaming experience.

## Features

- **Server-Side Logic:** Developed using Express, HTTP, Socket.io, and chess.js libraries to manage the game state and WebSocket connections.
- **Express Application:** Configured to handle HTTP requests and manage WebSocket connections for real-time gameplay.
- **Player Role Assignment:** Ensures smooth game flow by managing multiple connections and assigning player roles dynamically.
- **Drag-and-Drop Functionality:** Integrated on the chessboard for intuitive piece movement, updating the game state in real-time.
- **Dynamic Front-End:** Handles WebSocket connections, DOM manipulations, and chessboard updates to reflect the current game state.

## Technologies Used

- **JavaScript:** Core programming language for both server and client-side logic.
- **Express:** Server framework to handle HTTP requests and set up WebSocket connections.
- **Socket.io:** Library for real-time, bidirectional communication between server and clients.
- **chess.js:** Library to manage and validate chess game logic.
- **EJS:** Templating engine for generating dynamic HTML content.
- **HTML/CSS:** For structuring and styling the user interface.
