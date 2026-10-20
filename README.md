# Express Health Check

Minimal Node.js + Express API with a health check route.

## Setup
```bash
npm install
cp .env.example .env   # optional, defaults to PORT=3000
npm start              # or: npm run dev (auto-restart with nodemon)
```

## Test the health route
```bash
curl http://localhost:3000/health
```
Example response:
```json
{ "status": "ok", "uptime": 12, "timestamp": "2026-10-19T10:00:00.000Z" }
```

## Dependencies
express, dotenv, cors, morgan, nodemon (dev)
