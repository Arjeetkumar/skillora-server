# Skillora - Server (Starter)

This is a starter Node.js + Express backend for Skillora (MVP).

## What's included
- Express server
- MongoDB (Mongoose) connection
- JWT auth (register / login)
- Basic user model (student, client, admin)
- Protected route to get/update profile

## Quick start (local)

1. Install Node.js >= 18 and MongoDB
2. Copy `.env.example` to `.env` and set `MONGODB_URI` and `JWT_SECRET`
3. Install dependencies:
   npm install
4. Start dev server:
   npm run dev
5. API endpoints:
   - POST /api/auth/register
   - POST /api/auth/login
   - GET /api/users/me (requires header x-auth-token: <token>)

## Notes
- This is the backend starter. Frontend (React + Vite + Tailwind) will connect to these APIs.
