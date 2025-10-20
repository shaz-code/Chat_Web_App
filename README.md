🗨️ Chat Web App

A simple, real-time web chat application built with JavaScript, designed to let users send and receive messages instantly through a clean web interface.

This project is a full-stack setup — combining a lightweight backend (Node.js + Express) and a frontend (HTML, CSS, and JS) to create a seamless chatting experience.

🚀 Features

💬 Real-time messaging — Send and receive messages instantly without page reloads

⚙️ Frontend + Backend setup — Organized into separate folders for easy development

👥 Multiple users support — Chat with other connected users live

🧠 Scalable structure — Ready for features like user authentication, chat rooms, and message history

🎨 Simple UI — Clean and minimal design that’s easy to extend or restyle

🧩 Tech Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript
Backend	Node.js, Express.js
Real-time Communication	Socket.io (or WebSockets, depending on your implementation)
Package Manager	npm
🗂️ Project Structure
Chat_Web_App/
│
├── backend/           # Server-side logic (API routes, socket handling, etc.)
├── frontend/          # Client-side files (HTML, CSS, JS)
├── package.json       # Project dependencies and scripts
└── README.md          # You’re reading it :)

⚡ Getting Started

Follow these steps to run the app locally 👇

1️⃣ Clone the repository
git clone https://github.com/shaz-code/Chat_Web_App.git

2️⃣ Go to the project directory
cd Chat_Web_App

3️⃣ Install dependencies
npm install

4️⃣ Run the backend server
cd backend
node server.js

5️⃣ Open the frontend

Open the frontend/index.html file in your browser

Or serve it using a simple local server (like Live Server in VS Code)

🧠 How It Works

When a user opens the frontend, it connects to the backend via Socket.io (WebSockets).

Each message sent by a user is broadcasted to all connected clients in real time.

The backend handles communication, connection management, and message flow.

The UI updates instantly without reloading the page.
