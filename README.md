# MemePop — Viral App Prototype

This is a GitHub-ready prototype for **MemePop**, a small viral app demo with:
- Node/Express backend (SQLite) + Socket.io realtime
- React frontend (plain Create React App style)
- Short share links, upvotes, views, trending score, referral code param

## Quick start (local)

Requirements: Node.js 18+ and npm.

1. Start backend
```bash
cd backend
npm install
npm start
```
Backend runs at `http://localhost:4000`.

2. Start frontend
```bash
cd frontend
npm install
npm start
```
Frontend runs at `http://localhost:3000`.

## Repo structure
```
meme-pop/
├─ backend/
└─ frontend/
```

## Notes
- This is a prototype intended for learning / hacking — **do not** use in production without adding authentication, rate limits, validation, and security hardening.
- To deploy, set `REACT_APP_API_URL` in the frontend `.env` to point at your backend.
