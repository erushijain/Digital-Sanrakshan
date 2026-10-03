# Digital संरक्षण
AI-powered Scam Detection, Receiver Consent & Loan Risk Management. A frontend-only hackathon prototype with synthetic data.

## Install & run
    npm install
    npm run dev
Demo login: Customer ID `DT1001`, PIN `1234`, or "Continue with Demo Account".

## Features
Consent Gate (accept / return / flag / mock report), Behavioral Twin charts, Scam Classifier with reason codes, interactive ScamGraph, Loan Guardian with savings planner, Action Center, Audit Ledger with CSV export, transactions with drawer, customer 360, global search, notifications. State persists in localStorage (Settings → Reset demo).

## Stack
React 18, Vite, React Router, Recharts, Lucide, Framer Motion (page transitions).

## Structure
`src/data` synthetic data · `src/services/riskEngine.js` rule-based scoring · `src/hooks/useStore.jsx` global state + audit logging · `src/components` shared UI · `src/pages` routes.

## Mock AI architecture
Scores come from transparent rules (amount vs usual, new sender, timing, scam keywords, device, ScamGraph link). Not a trained model.

## Known demo limitations
No backend; government reporting is a mock; ScamGraph is a custom SVG (no React Flow); targets (<150 ms, ≥90% recall, ≤2% FPR, 10-day lead) are goals, not results.
