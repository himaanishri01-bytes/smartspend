# 💡 SmartSpend — Student FinTech Intervention Engine

**SmartSpend** is a full-stack FinTech web application designed specifically for college students living on fixed allowances. Unlike traditional budgeting tools that act as passive receipt trackers after money is spent, SmartSpend introduces **pre-spend friction** and **active intervention** to curb impulsive spending and direct saved micro-funds toward long-term financial goals.

---

## 🎯 Core Features

- 🛡️ **Budget Interceptor:** Evaluates planned non-essential purchases before execution and offers micro-savings redirection prompts.
- 🏷️ **Contextual Ledger:** Replaces generic categorization with specific student context tags (e.g., "Dad Allowance", "Hostel Canteen").
- 📊 **Dynamic Goal Simulator:** Calculates how daily expense reductions impact major goal timelines (e.g., funding a laptop or certification course).
- 📈 **Real-Time Analytics:** Tracks weekly spending velocity to detect mid-month allowance leaks early.

---

## 🏗️ Tech Stack & CS Concepts

- **Frontend:** React.js, TailwindCSS / CSS3, Axios
- **Backend:** Node.js, Express.js
- **Database:** MySQL (Relational Schema with Foreign Key Constraints)
- **Object-Oriented Programming (OOP):** Domain modeling using class encapsulation, inheritance, and modular service patterns (`UserAccount`, `Transaction`, `BudgetRule`).
- **Data Structures & Algorithms (DSA):**
  - **Hash Maps:** O(1) threshold lookups for category limits.
  - **Max-Heap:** Real-time ranking of top wasteful spending categories.
  - **Sliding Window Algorithm:** 7-day rolling evaluation to detect spending spikes.

---

## 📁 Repository Structure

```text
smartspend/
├── backend/
│   ├── src/
│   │   ├── algorithms/     # DSA implementations (Heap, Sliding Window)
│   │   ├── config/         # MySQL DB connection pool
│   │   ├── controllers/    # API Request Handlers
│   │   ├── models/         # OOP Domain Class Models
│   │   └── routes/         # Express API Endpoints
│   └── database/           # MySQL Schema scripts & seed data
├── frontend/               # React.js web interface
└── README.md
