# Health Access Simplifier

A full-stack, mobile-first healthcare booking application focused on one critical feature: booking doctor appointments quickly for first-time and low-literacy smartphone users.

## What is included

- Frontend: React + Vite mobile UI with 7 booking screens
- Backend: Node.js + Express API for OTP flow and appointment booking
- DevOps: Dockerfiles for frontend/backend, Docker Compose, GitHub Actions CI

## Screens implemented

1. Sign In
2. OTP Verification
3. Home (Booking Focus)
4. Hospital Selection
5. Doctor Selection
6. Date and Time Selection
7. Confirmation

## Local development

### 1) Backend

```bash
cd backend
npm install
npm run dev
```

Backend runs on: http://localhost:4000

### 2) Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on: http://localhost:5173

## Docker run

```bash
docker compose up --build
```

- Frontend: http://localhost:8080
- Backend API: http://localhost:4000/api/health

## Demo OTP

Use OTP: `1234`

## Key UX design choices

- Large, rounded controls for easy touch targets
- Soft blue/green/white palette with high contrast text
- Minimal single-path booking flow to reduce cognitive load
- Clear icons and readable font for fast comprehension
- Consistent spacing and card patterns across all screens
