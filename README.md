# 💬 React ChatApp – Real-Time Messaging Platform

<div align="center">
  <h1>⚡ Modern Web Chat Application</h1>
  <p><strong>Secure, real-time messaging with JWT authentication and WebSockets</strong></p>

  <p>
    <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
    <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
    <img src="https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101" alt="Socket.io" />
    <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  </p>
</div>

---

## 📸 Screenshots

<div align="center">
  <img src="client/src/assets/screenshots/Chatroom.png" alt="Chat Interface" width="250" />
  <img src="client/src/assets/screenshots/Register.png" alt="Registration Page" width="250" />
  <img src="client/src/assets/screenshots/Login.png" alt="Login Page" width="250" />
  <br/><br/>
  <img src="client/src/assets/screenshots/Failed-Login.png" alt="Failed Login" width="250" />
  <img src="client/src/assets/screenshots/Error.png" alt="Error Handling" width="250" />
  <img src="client/src/assets/screenshots/Color-Palette.png" alt="Color Palette" width="250" />
</div>

---

## ✨ Features

| Feature               | Description                                                              |
|-----------------------|--------------------------------------------------------------------------|
| 🔐 **JWT Auth**        | Secure login and registration with token-based authentication            |
| ⚡ **Real-Time Chat**  | Instant messaging with WebSocket communication via Socket.io             |
| 💬 **Persistent Chat** | Conversations stored securely in PostgreSQL                             |
| 📢 **Notifications**  | User feedback with React Toastify                                        |
| 🎨 **Styled UI**       | Consistent look & feel with Styled Components                           |

---

## 🛠️ Tech Stack

### 🔹 Frontend
- React.js
- Redux
- React Router
- Styled Components
- Socket.io-client
- React Toastify

### 🔸 Backend
- Node.js + Express
- PostgreSQL + Sequelize
- Socket.io
- Bcrypt
- JWT (JSON Web Tokens)

---

## 🚀 Getting Started

### ✅ Prerequisites
- Node.js v14+
- PostgreSQL installed and running

---

### 📦 Installation

``bash
# 1. Clone the repo
git clone https://github.com/your-username/react-chatapp.git
cd react-chatapp

# 2. Install client dependencies
cd client
npm install

# 3. Install server dependencies
cd ../server
npm install

⚙️ Configuration
Create .env files in both client/ and server/ directories.

Sample .env for server:
env
Copy
Edit
PORT=5000
DB_NAME=your_database_name
DB_USER=your_username
DB_PASSWORD=your_password
DB_HOST=localhost
JWT_SECRET=your_jwt_secret
▶️ Running the App
bash
Copy
Edit
# Start the backend server
cd server
npm start

# In a new terminal, start the frontend
cd ../client
npm start
📚 What I Learned
🔧 How WebSockets and real-time messaging work with Socket.io

🔐 Building secure authentication flows with JWT

⚛️ Managing global state using Redux

🗃️ PostgreSQL database modeling using Sequelize ORM

🧑‍🎨 Responsive UI development using Styled Components

🧩 Challenges Faced
Socket.io Integration: Managing real-time connections and user sessions

JWT Auth: Refreshing tokens, securing routes

Redux with Sockets: Syncing socket events with app state

DB Modeling: Designing scalable message schema

UX Handling: Toasts, error states, and feedback

🔮 Future Enhancements
✅ Read receipts

📁 File sharing

📣 Chat rooms/channels

⌨️ Typing indicators

🟢 Online/offline presence detection

🤝 Contributing
Contributions are welcome! 🚀

Fork the repo

Create a new branch: git checkout -b feature/FeatureName

Commit your changes: git commit -m 'Add feature'

Push to the branch: git push origin feature/FeatureName

Open a Pull Request

