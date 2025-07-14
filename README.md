# 🌀 Nebulo - Real-Time Chat App

**Nebulo** is a full-stack, real-time chat application built with modern web technologies. It supports authentication, socket-powered real-time messaging, profile updates, online user tracking, and more.

> 💬 Deployed Frontend: [https://nebulo-six.vercel.app](https://nebulo-six.vercel.app)  
> 🛠️ Deployed Backend: [https://nebulo-server-production.up.railway.app](https://nebulo-server-production.up.railway.app)

---

## 🚀 Features

- 🔐 JWT-based authentication (Signup, Login, Logout)
- 📡 Real-time messaging using **Socket.IO**
- 🟢 Online user detection
- 👤 Profile picture upload via **Cloudinary**
- 🧠 Zustand state management
- 🎨 Dark/Light theme support
- 🧾 Protected routes with persistent session via **HTTP-only cookies**

---

## 🧱 Tech Stack

### Frontend:
- React + Vite
- Zustand (for state)
- Tailwind CSS
- React Router
- Axios (with credentials)
- socket.io-client
- react-hot-toast

---

## 🖼️ Screenshots

### Here is the Demo video:
https://drive.google.com/drive/folders/1N_hNEiVeMrTDsiJYdIYHPODOxQgnDq0G?usp=sharing
### 💬 Chat UI Example:
<img width="1919" height="911" alt="image" src="https://github.com/user-attachments/assets/62c9b131-82f6-47b3-babf-3c6553bc11d0" />
### 🔐 Login Page:
<img width="1919" height="914" alt="image" src="https://github.com/user-attachments/assets/4e5ddd5c-9866-4238-87d4-535c316d2b81" />

---

### Backend:
- Node.js + Express
- MongoDB + Mongoose
- JWT + Cookies
- Socket.IO
- Cloudinary (image upload)
- cookie-parser, cors, dotenv

---
# Create .env file
PORT=5001

MONGO_URI=your_mongodb_uri

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development

```
cd Nebulo-app
npm install
npm run dev

cd Nebulo-server
npm install
node index.js
```
