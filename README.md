# Digital-Sanrakshan
# 🛡️ Digital संरक्षण

### AI-Powered Scam Detection · Receiver Consent · Loan Risk Management

> **A frontend-only fintech security prototype built for hackathons — powered by synthetic data, transparent risk rules, and explainable decision-making.**

---

## ✦ Overview

**Digital संरक्षण** is a modern fintech safety platform designed to help customers **detect scams, make informed financial decisions, and manage loan risk**.

The prototype brings together transaction intelligence, behavioral analysis, consent verification, scam-network visualization, and financial planning into one unified dashboard.

### What it focuses on

* 🛡️ **Scam Prevention**
* 🔐 **Receiver Consent**
* 🧠 **Explainable Risk Intelligence**
* 💰 **Loan Risk Management**
* 📊 **Financial Behavior Analysis**
* 📋 **Transparent Audit Trails**

---

## 🚀 Getting Started

```bash
npm install
npm run dev
```

### Demo Access

**Customer ID:** `DT1001`
**PIN:** `1234`

Or simply choose **Continue with Demo Account**.

---

## ✨ Features

| Module                  | What it does                                                       |
| ----------------------- | ------------------------------------------------------------------ |
| 🔐 **Consent Gate**     | Accept, return, flag or mock-report suspicious transactions        |
| 🧬 **Behavioral Twin**  | Visualizes customer spending and transaction patterns              |
| 🚨 **Scam Classifier**  | Identifies suspicious activity with transparent reason codes       |
| 🕸️ **ScamGraph**       | Explores connections between transactions, users and scam entities |
| 🏦 **Loan Guardian**    | Assesses loan risk with an interactive savings planner             |
| ⚡ **Action Center**     | Provides quick actions for detected financial risks                |
| 📜 **Audit Ledger**     | Records system actions with CSV export                             |
| 💳 **Transactions**     | Explore transaction details through an interactive drawer          |
| 👤 **Customer 360**     | Unified customer financial overview                                |
| 🔎 **Global Search**    | Quickly find customers, transactions and system information        |
| 🔔 **Notifications**    | Real-time-style alerts for the demo environment                    |
| 💾 **Persistent State** | Demo state is maintained using `localStorage`                      |

---

## 🧠 Explainable Risk Engine

Digital संरक्षण does **not** pretend to use a trained AI model.

Instead, the prototype uses a transparent, rule-based scoring engine:

```text
Transaction Risk
      ↓
Amount vs. Usual Behavior
      +
New Sender
      +
Unusual Timing
      +
Scam Keywords
      +
Device Signals
      +
ScamGraph Connections
      ↓
Risk Score + Reason Codes
      ↓
Recommended Action
```

This makes every risk decision **traceable, understandable, and demonstrable** during a hackathon presentation.

---

## 🏗️ Architecture

```text
Synthetic Data
      ↓
Consent Gate
      ↓
Feature Engine
      ↓
Risk / AI Engine
      ↓
Explainability Layer
      ↓
Action Layer
      ↓
Dashboard + Audit Ledger
```

### Core Data

Customers · Transactions · Devices · Merchants · Loans · Scam Reports

---

## 🧩 Tech Stack

**Frontend**

* React 18
* Vite
* React Router

**Visualization**

* Recharts
* Custom SVG ScamGraph

**UI / Interaction**

* Lucide
* Framer Motion

**State**

* React Hooks
* `localStorage`

**Risk Intelligence**

* Transparent rule-based scoring
* Synthetic financial data

---

## 📁 Project Structure

```text
src/
├── data/
│   └── synthetic data
│
├── services/
│   └── riskEngine.js
│
├── hooks/
│   └── useStore.jsx
│
├── components/
│   └── shared UI
│
└── pages/
    └── application routes
```

---

## 🔍 What Makes the Prototype Different?

### **Explainable by Design**

Every risk score can be traced back to understandable signals rather than an unexplained prediction.

### **One Financial Safety Layer**

Scam detection, consent, behavioral intelligence and loan planning exist within the same experience.

### **Action-Oriented**

The system doesn't stop at identifying risk — the prototype connects detection to possible customer actions.

### **Audit-Ready**

Important system interactions are logged, allowing the demo to demonstrate transparency and traceability.

---

## 📈 Prototype Targets

> **These are system goals, not production results.**

| Target                 |      Goal |
| ---------------------- | --------: |
| ⚡ p95 Latency          | `<150 ms` |
| 🎯 Scam Recall         |    `≥90%` |
| 🛑 False Positive Rate |     `≤2%` |
| ⏳ EMI Alert Lead Time  | `10 days` |

---

## ⚠️ Demo Limitations

This project is intentionally a **frontend-only hackathon prototype**.

* No production backend
* Synthetic/demo data only
* Government reporting is mocked
* ScamGraph uses custom SVG rather than React Flow
* Risk scores come from rules, not a trained ML model
* Performance and detection targets are **aspirational goals, not measured production results**

---

## 🔄 Reset Demo

All demo state is persisted locally.

To return to the initial state:

**Settings → Reset Demo**

---

## 🌐 Vision

> **Detect risk. Explain it. Give people control.**

Digital संरक्षण explores how fintech interfaces can make financial safety **more transparent, proactive, and human-centered** — without hiding important decisions behind a black box.

---

### 🛡️ Digital संरक्षण

**Protect transactions. Empower decisions. Build financial trust.**
