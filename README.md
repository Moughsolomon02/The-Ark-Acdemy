# The Ark Academy - School Management Portal

This project is a full-stack school management system for The Ark Academy, built with:

- **Frontend**: React + Vite + TailwindCSS
- **Backend**: Node.js + Express + MongoDB

## 📦 Folder Structure

```
The-Ark-Academy/
├── backend/
├── frontend/
├── .gitignore
├── README.md
```

## 🚀 Deployment

### Backend (Render)
1. Push `/backend` to GitHub.
2. Go to [render.com](https://render.com), create new web service from GitHub.
3. Set environment variables from `.env`.
4. Set Start Command: `node server.js`

### Frontend (Vercel)
1. Push `/frontend` to GitHub.
2. Go to [vercel.com](https://vercel.com), import GitHub repo.
3. Set Environment Variable: `VITE_API_BASE_URL=https://your-backend-url.onrender.com/api`