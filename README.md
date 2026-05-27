# Multiplayer Snake Game

A real-time multiplayer snake game built with Node.js, Express, and Socket.io.

## Quick Start

```bash
npm install
npm start
```

Open browser at `http://localhost:3000`

## Features

- Real-time multiplayer via WebSocket
- Bot players with AI direction control
- Multiple food types (normal, golden, super, swap)
- Player collision and kill system
- Score tracking and player statistics
- Custom wall placement
- Player image and background upload
- Spectator mode

## Project Structure

```
├── app.js                     # Entry point
├── app/
│   ├── configs/               # Board and server configuration
│   ├── controllers/           # Game controller (main game loop)
│   ├── models/                # Data models (player, food, coordinate, etc.)
│   ├── services/              # Business logic services
│   └── views/                 # HTML templates
├── public/                    # Frontend assets (JS, CSS, images)
└── test/                      # Unit tests
```

## Tech Stack

- Node.js + Express
- Socket.io (real-time communication)
- HTML5 Canvas (rendering)
- Mocha + Chai (testing)
