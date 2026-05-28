<div align="center">

<!-- Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0a1628,100:0d2137&height=180&section=header&text=📚%20StudyFlow&fontSize=60&fontColor=4f9eff&animation=fadeIn&fontAlignY=38&desc=Study%20Progress%20Tracking%20System%20%7C%20React%20%2B%20Node.js&descAlignY=60&descSize=18&descColor=8b949e" />

<br/>

<!-- Badges -->
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

<br/>

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-progress--tracking--system.vercel.app-4f9eff?style=for-the-badge)](https://progress-tracking-system.vercel.app/)

<br/>

> **StudyFlow** is a full-stack study progress tracking system that helps students manage tasks, monitor productivity, and visualize their learning journey — all in one clean, responsive dashboard.

</div>

---

## 📱 Screenshots

<div align="center">

<table>
<tr>

<td align="center">
<img src="./screenshots/dashboard.png" width="600" alt="Dashboard"/>
<br/>
<b>📊 Dashboard</b>
</td>

<td align="center">
<img src="./screenshots/analytics.png" width="600" alt="Analytics"/>
<br/>
<b>📈 Analytics</b>
</td>

<td align="center">
<img src="./screenshots/tasks.png" width="600" alt="Tasks"/>
<br/>
<b>✅ Task Tracker</b>
</td>

</tr>
</table>

</div>

---

## ✨ Features

- 🔐 **User Authentication** — Secure login & registration with JWT
- 📊 **Progress Dashboard** — Visualize your study progress at a glance
- ✅ **Task Management** — Create, update, and delete study tasks
- 📈 **Real-time Monitoring** — Track completion rates live
- 🎯 **Goal Setting** — Set targets and measure how far you've come
- 📱 **Fully Responsive** — Works seamlessly on all screen sizes
- 🌐 **Live Deployed** — Hosted on Vercel for instant access

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-----------|
| ⚛️ Frontend | React 18 + Vite |
| 🎨 Styling | Tailwind CSS |
| 🔌 HTTP Client | Axios |
| ⚙️ Backend | Node.js + Express.js |
| 🗄️ Database | MongoDB Atlas |
| 🔐 Auth | JWT (JSON Web Tokens) |
| 🚀 Deployment | Vercel |

---

## 📁 Project Structure

```
StudyFlow/
├── src/                  # React (Vite) frontend
│   ├── components/       # UI components
│   ├── pages/            # Route pages
│   └── utils/            # Helpers & API calls
├── backend/              # Node.js + Express API
│   └── .env              # MONGO_URI, JWT_SECRET, PORT
├── dist/                 # Production build
├── index.html
├── vite.config.js
├── tailwind.config.js
└── vercel.json
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js ≥ 18
- MongoDB Atlas account
- Git

---

### 🖥️ Backend Setup

```bash
# 1. Clone the repository
git clone https://github.com/Om-005/StudyFlow.git
cd StudyFlow

# 2. Navigate to backend
cd backend

# 3. Install dependencies
npm install

# 4. Create .env file
touch .env
```

Add to `.env`:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

```bash
# 5. Start the backend server
npm start
```

Server runs at `http://localhost:5000` ✅

---

### 💻 Frontend Setup

```bash
# From project root
npm install

# Start development server
npm run dev
```

App runs at `http://localhost:5173` ✅

```bash
# Build for production
npm run build
```

---

## ☁️ Deployment

The app is deployed on **Vercel** with the following config (`vercel.json`):

| Service | Platform |
|---------|---------|
| Frontend | [Vercel](https://vercel.com) |
| Backend API | [Render](https://render.com) / [Railway](https://railway.app) |
| Database | [MongoDB Atlas](https://cloud.mongodb.com) |

🔗 **Live:** [https://progress-tracking-system.vercel.app](https://progress-tracking-system.vercel.app/)

---

## 🔮 Future Improvements

- 📊 Advanced analytics with charts & graphs
- 🔔 Study reminders & notifications
- 🤝 Collaboration & shared study groups
- 📱 React Native mobile app
- 🏆 Streaks & achievement badges
- 🤖 AI-powered study recommendations

---

## 👨‍💻 Authors

<div align="center">

<table>
  <tr>
    <td align="center">
      <b>Om Wadghule</b><br/>
      <a href="https://github.com/Om-005">
        <img src="https://img.shields.io/badge/GitHub-Om--005-181717?style=flat-square&logo=github" />
      </a>
      &nbsp;
      <a href="http://www.linkedin.com/in/om-wadghule-2005id">
        <img src="https://img.shields.io/badge/LinkedIn-Om%20Wadghule-0077B5?style=flat-square&logo=linkedin" />
      </a>
    </td>
    <td align="center">
      <b>Pritesh Jadhav</b><br/>
      <a href="https://github.com/Pritesh-Jadhav">
        <img src="https://img.shields.io/badge/GitHub-Pritesh--Jadhav-181717?style=flat-square&logo=github" />
      </a>
    </td>
  </tr>
</table>

</div>

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repo
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

<div align="center">

⭐ **If you found StudyFlow helpful, give it a star!** ⭐

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d2137,50:0a1628,100:0d1117&height=100&section=footer" />

</div>
