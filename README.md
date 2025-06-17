
# 🚀 MindSpark – AI-Powered Microlearning Platform

**MindSpark** is an AI-powered microlearning platform built for fast, focused learning. Whether you're a student, a developer, or a curious mind, MindSpark delivers bite-sized knowledge when and where you need it — no fluff, just pure learning.

> ⚡ "Microlearning meets AI – with real-time interaction, gamification, and a smooth experience built for modern learners."

---

## 🌟 Features

- 🎓 **Bite-Sized Lessons** – Learn fast with short videos, quick quizzes, and focused content.
- 💬 **Real-Time Chat** – Interact live with other learners during lessons via native WebSocket integration.
- 🏆 **Gamification** – Earn XP, badges, and maintain learning streaks to stay motivated.
- 📈 **Progress Tracking** – Visualize your growth with dashboards and analytics.
- 🗨️ **Community Forums** – Ask questions, discuss topics, and help others in a dedicated space.
- 🎥 **Video Upload System** – Upload and manage lesson videos securely with Cloudinary.
- 🧠 **AI-Powered** – Leverage smart content suggestions and Q&A generation.
- 🖥️ **Modern UI/UX** – Clean, responsive, accessible design built with Tailwind CSS and React.

---

## 🛠️ Tech Stack

### Frontend:
- ⚛️ React (Vite)
- 🎨 Tailwind CSS
- ☁️ Cloudinary (Media uploads)

### Backend:
- 🟢 Node.js + Express
- 🍃 MongoDB Atlas
- 🔐 JWT Authentication
- 🧠 AI Integrations (OpenAI API, custom logic)
- 🔌 Native WebSockets for chat

### DevOps:
- 🚀 Deployment via Render
- 🛢️ Database hosted on MongoDB Atlas

---

## 📁 Project Structure

```

MindSpark/
├── Backend/
│   └── src/
│       ├── config/
│       ├── controllers/
│       ├── middlewares/
│       ├── models/
│       ├── routes/
│       ├── utils/
│       └── server.ts
├── Frontend/
│   └── src/
│       ├── Components/
│       ├── Pages/
│       ├── assets/
│       ├── features/
│       ├── icons/
│       ├── utils/
│       ├── App.jsx
│       ├── main.jsx
│       └── firebase.js

````

---

## 🚀 Getting Started

### 1️⃣ Clone the repo

```bash
git clone https://github.com/iramsk02/MindSpark.git
cd MindSpark
````

### 2️⃣ Setup the Backend

```bash
cd Backend
npm install
```

#### 📦 Backend Scripts

| Script        | Description                             |
| ------------- | --------------------------------------- |
| `npm run dev` | Compile TypeScript and start dev server |
| `npm start`   | Run compiled server (after `tsc -b`)    |

> Make sure to create a `.env` file with required Mongo URI, JWT secrets, etc.

### 3️⃣ Setup the Frontend

```bash
cd ../Frontend
npm install
```

#### 📦 Frontend Scripts

| Script            | Description              |
| ----------------- | ------------------------ |
| `npm run dev`     | Start Vite dev server    |
| `npm run build`   | Build for production     |
| `npm run preview` | Preview production build |
| `npm run lint`    | Run ESLint on codebase   |

> Configure your Firebase and Cloudinary credentials in `firebase.js` and `.env` respectively.

---

## 🧪 Environment Variables

Both frontend and backend use `.env` files for secrets and config.

**Backend `.env`:**

```
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
CLOUDINARY_CLOUD_NAME=...
```



---

## 🌍 Deployment

* **Frontend** is deployed using **Render** + **Vite**
* **Backend** is deployed via **Render Web Service**
* **Database** is hosted on **MongoDB Atlas**
* **Media Storage** is managed via **Cloudinary**

---

## 🤯 What I Learned

This project taught me a **lot** — from:

* Setting up secure auth with JWT + Firebase
* Building real-time chat with native WebSockets
* Uploading and managing media securely
* Designing user-friendly interfaces with React + Tailwind
* Integrating AI features for smart content
* Making the app responsive and accessible for everyone

It truly pushed me out of my comfort zone and helped me grow as a full-stack dev.

---

## 🙌 Let's Connect!

If you're into **edtech**, **microlearning**, or just love building cool stuff — I’d love your feedback and thoughts!

Made with ❤️ by [@iramsk02](https://github.com/iramsk02)

---

