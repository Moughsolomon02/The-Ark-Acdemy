
# The Ark Academy – School Management Portal

## Overview

**The Ark Academy** is a full-featured school management system built with a focus on excellence, clarity, and purpose. 
This platform helps manage students, staff, parents, announcements, performance tracking, and donations in one unified interface.

> _"Equipping students to walk in the wisdom of God and manifest His excellence in all they do."_

---

## ✨ Features

- Secure student/staff/parent login system (JWT Auth)
- Student performance dashboard (tests, assignments, correction requests)
- Staff dashboard with hierarchy, profile previews, and task tabs
- Parent dashboard with announcements and donations
- Proprietor dashboard with founder quotes and mission
- Fully responsive and attractive UI using TailwindCSS
- Node.js + Express + MongoDB backend
- Vite + React frontend
- Admin-protected API routes

---

## 🚀 Tech Stack

- **Frontend**: React, TailwindCSS, Axios, Vite
- **Backend**: Node.js, Express, MongoDB, Mongoose
- **Auth**: JWT (JSON Web Tokens)
- **Deployment**: Vercel (Frontend), Render/Railway (Backend)

---

## 🛠 Setup Instructions

### 1. Backend
```bash
cd backend
npm install
touch .env
# Add the following variables to .env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
npm run start
```

### 2. Frontend
```bash
cd frontend
npm install
touch .env
# Add the following variables to .env
VITE_API_BASE_URL=https://your-live-backend.com/api
npm run dev
```

---

## 👤 Admin Test Accounts

| Role     | Email                 | Password     |
|----------|----------------------|--------------|
| Admin    | admin@arkacademy.com | Admin@123    |
| Teacher  | teacher@ark.com      | Teacher@123  |
| Student  | student@ark.com      | Student@123  |
| Parent   | parent@ark.com       | Parent@123   |

---

## 📫 Contact / Demo Requests

Interested in launching a similar system for your school?
Reach out to our development team today!

---

## 🕊 Vision

> *"A call to walk on the excellent and permanent path predestined by God, bringing others into a life full of riches, excellence, and abundant supply—The Ark: Christ Riches in Glory."*

---

© 2025 The Ark Academy. Built with purpose and excellence.
