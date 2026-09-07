# WorkspaceHub

WorkspaceHub is a workspace booking SaaS for discovering desks, meeting rooms and private offices, checking booking conflicts, and managing reservations.

## Features
- Responsive workspace marketplace
- User registration and login
- JWT authentication
- Password hashing with bcrypt
- Workspace search and filtering
- Desk, meeting room and private office listings
- Date/time booking
- Booking conflict prevention
- Personal booking dashboard
- REST API
- MongoDB persistence with in-memory fallback

## Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express, MongoDB, Mongoose, JWT, bcrypt

## Run locally
```bash
cd backend
npm install
copy .env.example .env
npm run dev
```
Open `frontend/index.html` with VS Code Live Server.

API: `http://localhost:5000`

## API
- `GET /api/health`
- `POST /api/auth/register`
- `POST /api/auth/login`
- `GET /api/spaces`
- `POST /api/bookings`
- `GET /api/dashboard`
