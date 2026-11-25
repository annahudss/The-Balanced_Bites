# The Balanced Bites

A personalised meal-planning web application built with React, Node.js, Express and MongoDB.

## Requirements
- Node.js (LTS)
- MongoDB connection string (for database features)
- Spoonacular API key (for recipe search integration)

## Setup

### Backend
```bash
cd backend
npm install
```
Copy `backend/.env.example` to `backend/.env` and fill in your own values. Required settings include `MONGO_URI`, `JWT_SECRET`, `JWT_REFRESH_SECRET`, and `SPOONACULAR_API_KEY`. Never commit or share `.env`.

### Frontend
Open a second terminal from the project root:
```bash
cd frontend
npm install
```

### Run
In the backend terminal (inside `backend`):
```bash
npm run dev
```
In the frontend terminal (inside `frontend`):
```bash
npm run dev
```
Open the local URL printed by Vite (usually http://localhost:5173).

## Project structure
- `backend/` — Express API, authentication, database models and routes
- `frontend/` — React + Vite user interface

## Security note
This portfolio copy has had hardcoded MongoDB connection strings removed. Database and API-key-dependent features require your own environment variables. If credentials from an earlier public version were real, ask the database owner to rotate them.
