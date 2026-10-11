# Broke But Functional — Survive the Month

A React + Vite interactive personal-finance prototype for Prompt Run 2026. Users can explore how expenses, subscriptions, savings goals, and simulated purchases affect a ₹10,000 / 30-day budget.

## Features
- Budget dashboard: balance, daily allowance, savings progress, health indicator
- Expense entry with categories and deletion
- Subscription toggles
- Savings goals and ₹100 contributions
- Purchase decision simulator
- Balance chart and month-end pace estimate
- Responsive layout; LocalStorage persistence for expenses, goals, and subscriptions

## Stack
React, Vite, JavaScript, Recharts, Lucide React, CSS, LocalStorage.

## Run locally
Install Node.js LTS, then in this folder run:

```bash
npm install
npm run dev
```

Open the URL printed in the terminal (usually http://localhost:5173).

## Build
```bash
npm run build
npm run preview
```

## Vercel deployment
Push to GitHub, import the repository in Vercel, and use `npm run build` as the build command and `dist` as the output directory.

## Notes
- Demo data only; no bank connection or real payments.
- Forecast and health indicator are illustrative heuristics, not financial advice.
- LocalStorage is browser-specific, not a cloud database.
- Applied simulations are held in React state and do not persist after refresh.
- Test calculations and interactions before submission.
