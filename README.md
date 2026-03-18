# Realtime Code Editor

## Live Demo - https://realtime-collaborative-code-editor-d1gk.onrender.com

A collaborative, realtime code editor where multiple users can join a room, edit code together, see live updates, switch languages, and compile/run code.

## ✨ Features
- Realtime multi-user editing via WebSockets
- Room-based collaboration
- User presence + typing indicators
- Language switching
- Remote code compilation & execution
- Monaco Editor UI for rich code editing

## 🧰 Tech Stack

### Frontend
- **React** (Vite)
- **Monaco Editor** (`@monaco-editor/react`)
- **Socket.IO Client**
- **UUID**
- **CSS**

### Backend
- **Node.js**
- **Express**
- **Socket.IO**
- **Axios**

## 📁 Project Structure

```
Realtime-Code-Editor/
├── backend/
│   └── index.js             # Express + Socket.IO server
├── frontend/
│   ├── public/              # Static assets
│   ├── src/
│   │   ├── App.jsx           # Main UI + editor logic
│   │   ├── App.css           # Styling
│   │   ├── main.jsx          # App entry
│   │   └── assets/           # Images/assets
│   ├── index.html
│   ├── package.json
│   └── vite.config.js
├── package.json              # Backend dependencies + scripts
└── README.md
```

## 🚀 Getting Started

### 1. Install dependencies
```bash
npm install
cd frontend
npm install
```

### 2. Run the backend
```bash
npm run dev
```

### 3. Run the frontend
```bash
cd frontend
npm run dev
```
