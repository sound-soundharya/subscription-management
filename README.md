# Subscription Management Dashboard

Full-stack app with JWT authentication (Login + Register) built with React + Vite + Bootstrap (frontend) and Node.js + Express + MongoDB (backend).

---

## Project Structure

```
subscription-dashboard/
├── backend/
│   ├── config/db.js
│   ├── controllers/authController.js
│   ├── middleware/authMiddleware.js
│   ├── models/User.js
│   ├── routes/authRoutes.js
│   ├── server.js
│   ├── .env.example
│   └── package.json
└── frontend/
    ├── src/
    │   ├── context/AuthContext.jsx
    │   ├── components/ProtectedRoute.jsx
    │   ├── pages/Login.jsx
    │   ├── pages/Register.jsx
    │   ├── pages/Dashboard.jsx
    │   ├── services/api.js
    │   ├── App.jsx
    │   ├── main.jsx
    │   └── index.css
    ├── index.html
    ├── vite.config.js
    └── package.json
```

---

## Prerequisites

- Node.js >= 18.x
- MongoDB (local or Atlas)
- npm

---

## Setup & Run

### 1. Backend

```bash
cd backend
npm install


npm run dev       # development (nodemon)
# or
npm start         # production
```

Backend runs on **http://localhost:5000**

### 2. Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on **http://localhost:5173**

---
