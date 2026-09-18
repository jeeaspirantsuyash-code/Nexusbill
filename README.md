# NexusBill — Invoice & Billing Management System

A full-stack billing dashboard inspired by the supplied Stitch design.

## Stack
- Frontend: React + Vite
- Backend: Node.js + Express
- Persistence: JSON datastore
- Authentication: JWT
- Responsive dark LedgerFlow-style UI

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:5173

Demo account:
- Email: admin@nexusbill.local
- Password: admin123

## Production

```bash
npm run build
npm start
```

## Render
Build Command: `npm install && npm run build`
Start Command: `npm start`
Environment: `NODE_ENV=production`
Optional: `JWT_SECRET=change-this-in-production`
