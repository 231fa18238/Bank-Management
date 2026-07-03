# 🏦 Aura Bank - Integrated Fintech Ecosystem

<div align="center">

![Aura Bank Logo](https://img.shields.io/badge/AURA-BANK-135bec?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0wIDE4Yy00LjQxIDAtOC0zLjU5LTgtOHMzLjU5LTggOC04IDggMy41OSA4IDgtMy41OSA4LTggOHptLjMxLTguODZjLTEuNzctLjQ1LTIuMzQtLjk0LTIuMzQtMS42NyAwLS44NC43OS0xLjQzIDIuMS0xLjQzIDEuMzggMCAxLjkuNjYgMS45NCAxLjY0aDEuNzFjLS4wNS0xLjM0LS44Ny0yLjU3LTIuNDktMi45N1Y1SDEwLjl2MS42OWMtMS41MS4zMi0yLjcyIDEuMy0yLjcyIDIuODEgMCAxLjc5IDEuNDkgMi42OCAzLjY2IDMuMjEgMS45NS40NyAyLjM0IDEuMTUgMi4zNCAxLjg3IDAgLjUzLS4zOSAxLjM5LTIuMSAxLjM5LTEuNiAwLTIuMjMtLjcyLTIuMzItMS42NEg4LjA0Yy4xIDEuNyAxLjM2IDIuNjYgMi44NiAyLjk3VjE5aDIuMzR2LTEuNjdjMS41Mi0uMjkgMi43Mi0xLjE2IDIuNzItMi43NCAwLTIuMi0xLjktMi45NS0zLjY1LTMuNDV6Ii8+PC9zdmc+)

**A Modern, AI-Powered Banking Management System**

[![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=flat-square&logo=node.js)](https://nodejs.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-336791?style=flat-square&logo=postgresql)](https://www.postgresql.org/)
[![Python](https://img.shields.io/badge/Python-ML_API-3776AB?style=flat-square&logo=python)](https://www.python.org/)

[Live Demo](#demo) • [Features](#features) • [Installation](#installation) • [Documentation](#documentation)

## 👨‍💻 Author

**Asch Surya Kumar** — Full-stack developer and fintech enthusiast. Passionate about building secure, scalable banking systems with thoughtful UX and AI-powered features that make financial tools more accessible and intelligent.

</div>

---

## 📖 About

**Aura Bank** is a comprehensive, full-stack banking management system that brings together modern web technologies and AI-powered features. Designed for both customers and administrators, it provides a seamless digital banking experience with real-time transactions, intelligent loan analysis, fraud detection, and much more.

> 🎯 **Perfect for**: Learning fintech development, hackathon projects, or as a foundation for production banking applications.

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                              AURA BANK ARCHITECTURE                          │
└─────────────────────────────────────────────────────────────────────────────┘

                                    ┌──────────────┐
                                    │    Users     │
                                    │  (Customers  │
                                    │   & Admins)  │
                                    └──────┬───────┘
                                           │
                                           ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│                           🖥️  FRONTEND (React + TypeScript)                  │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐  ┌─────────────────────┐ │
│  │  Dashboard  │  │  Transfers  │  │    Loans    │  │   Admin Panel       │ │
│  │  • Balance  │  │  • IMPS     │  │  • Apply    │  │   • User Mgmt       │ │
│  │  • Charts   │  │  • NEFT     │  │  • Track    │  │   • Loan Approvals  │ │
│  │  • Alerts   │  │  • QR Pay   │  │  • AI Score │  │   • Analytics       │ │
│  └─────────────┘  └─────────────┘  └─────────────┘  └─────────────────────┘ │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐  ┌─────────────────────┐ │
│  │   Cards     │  │  Analytics  │  │   Support   │  │   3D Auth Page      │ │
│  │  • Debit    │  │  • Graphs   │  │  • Tickets  │  │   • Three.js        │ │
│  │  • Credit   │  │  • Reports  │  │  • AI Chat  │  │   • Animations      │ │
│  │  • Controls │  │  • Export   │  │  • FAQ      │  │   • Visual Effects  │ │
│  └─────────────┘  └─────────────┘  └─────────────┘  └─────────────────────┘ │
└───────────────────────────────────┬─────────────────────────────────────────┘
                                    │ REST API
                                    ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│                        ⚙️  BACKEND (Node.js + Express)                       │
│                                                                              │
│  ┌────────────────────────────────────────────────────────────────────────┐ │
│  │                           API Routes                                    │ │
│  │  /users  /accounts  /transactions  /loans  /cards  /support  /analytics│ │
│  └────────────────────────────────────────────────────────────────────────┘ │
│                                                                              │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐  ┌─────────────────────┐ │
│  │   Auth      │  │  Security   │  │   Ledger    │  │   Services          │ │
│  │  • JWT      │  │  • Rate     │  │  • Double   │  │   • Circuit Breaker │ │
│  │  • bcrypt   │  │    Limit    │  │    Entry    │  │   • Idempotency     │ │
│  │  • Refresh  │  │  • CORS     │  │  • Atomic   │  │   • Error Handling  │ │
│  └─────────────┘  └─────────────┘  └─────────────┘  └─────────────────────┘ │
└───────────────────────────┬───────────────────────────┬─────────────────────┘
                            │                           │
                            ▼                           ▼
┌───────────────────────────────────────┐  ┌──────────────────────────────────┐
│       🗄️  PostgreSQL Database         │  │     🤖  ML API (Python/Flask)    │
│                                       │  │                                  │
│  • Users & Authentication             │  │  • Fraud Detection Model         │
│  • Accounts & Transactions            │  │  • Loan Eligibility Predictor    │
│  • Loans & Cards                      │  │  • Expense Categorization        │
│  • Ledger Entries (Double-Entry)      │  │  • TF-IDF + Logistic Regression  │
│  • Support Tickets & Feedback         │  │  • Real-time Risk Assessment     │
└───────────────────────────────────────┘  └──────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│                          🔌  External Integrations                           │
│   ┌─────────────┐  ┌─────────────┐  ┌─────────────┐  ┌─────────────────────┐│
│   │   Ollama    │  │ DuckDuckGo  │  │  LangChain  │  │    Web Search       ││
│   │   (Local    │  │   Search    │  │   Agents    │  │    Integration      ││
│   │    LLM)     │  │     API     │  │             │  │                     ││
│   └─────────────┘  └─────────────┘  └─────────────┘  └─────────────────────┘│
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## ✨ Features

### 👤 Customer Features

| Feature | Description |
|---------|-------------|
| 🏠 **Smart Dashboard** | Real-time balance, recent transactions, spending charts, and fraud alerts |
| 💸 **Money Transfers** | Instant transfers via IMPS, NEFT, UPI, and QR code scanning |
| 💳 **Card Management** | Debit/Credit card controls, freeze/unfreeze, limit settings, PIN change |
| 📊 **Analytics** | Spending insights, category breakdown, income vs expense trends |
| 🏦 **Loan Services** | AI-powered loan eligibility, EMI calculator, loan tracking |
| 💰 **Fund Management** | Link external banks, cheque deposits, ATM locator, bill payments |
| 🎫 **Support Center** | Create tickets, AI chatbot assistance, FAQ section |
| 🔔 **Smart Alerts** | Fraud detection alerts, low balance warnings, transaction notifications |

### 👨‍💼 Admin Features

| Feature | Description |
|---------|-------------|
| 📈 **Overview Dashboard** | Bank-wide statistics, user growth, deposit trends |
| ✅ **Loan Approvals** | Review applications, AI risk scores, approve/reject with comments |
| 💳 **Card Approvals** | Credit card application management |
| 💬 **AI Chat Assistant** | Banking knowledge base with live web search capability |
| 📝 **Feedback Management** | Customer feedback analysis with AI-generated insights |
| ⚙️ **System Configuration** | Interest rates, maintenance mode, global settings |
| 📊 **Payment Tracking** | Monitor all transactions and loan repayments |

### 🤖 AI & ML Features

| Feature | Technology |
|---------|------------|
| 🔍 **Fraud Detection** | Machine learning model trained on transaction patterns |
| 📈 **Loan Risk Analysis** | DTI calculation, employment verification, credit scoring |
| 🏷️ **Expense Categorization** | TF-IDF + Logistic Regression for smart categorization |
| 💬 **AI Chat Support** | Ollama-powered local LLM for customer queries |
| 🌐 **Live Search** | DuckDuckGo integration for real-time banking information |

---

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern UI library with hooks
- **TypeScript 5.8** - Type-safe JavaScript
- **Vite 6** - Fast build tool and dev server
- **Tailwind CSS** - Utility-first styling
- **Three.js** - 3D graphics for immersive login page
- **Recharts** - Beautiful data visualizations
- **QRCode.react** - QR code generation

### Backend
- **Node.js** - JavaScript runtime
- **Express 4.18** - Web framework
- **TypeScript** - Type safety
- **PostgreSQL** - Relational database
- **JWT** - Secure authentication
- **bcrypt** - Password hashing
- **Zod** - Input validation

### Machine Learning
- **Python 3.x** - ML runtime
- **Flask** - ML API server
- **scikit-learn** - ML algorithms
- **joblib/pickle** - Model serialization
- **pandas/numpy** - Data processing

### AI & Integrations
- **Ollama** - Local LLM inference
- **LangChain** - AI agent framework
- **DuckDuckGo Search** - Web search integration

---

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- PostgreSQL 15+
- Python 3.9+
- Ollama (optional, for AI chat)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/9046balaji/bank-management-system.git
cd bank-management-system

# 2. Install all dependencies
npm run install:all

# 3. Set up environment variables
cp backend/.env.example backend/.env.local
# Edit the .env.local file with your database credentials

# 4. Initialize the database
# Run the SQL scripts in /database folder in order:
# - schema.sql
# - seed.sql

# 5. Start the application
npm start
```

### Running Individual Services

```bash
# Frontend only (port 5173)
npm run dev:frontend

# Backend only (port 5000)
npm run dev:backend

# ML API (port 5001)
npm run dev:ml

# All services together
npm run dev:all
```

---

## 📁 Project Structure

```
bank-management-system/
├── 📂 backend/               # Node.js Express API
│   ├── src/
│   │   ├── controllers/      # Request handlers
│   │   ├── db/               # Database connection
│   │   ├── middleware/       # Auth, rate limiting, errors
│   │   ├── routes/           # API endpoints
│   │   ├── services/         # Business logic
│   │   └── utils/            # Helper functions
│   └── tests/                # API tests
│
├── 📂 src/                   # Frontend source
│   ├── components/           # Reusable UI components
│   │   └── 3d/               # Three.js components
│   ├── contexts/             # React context providers
│   ├── hooks/                # Custom React hooks
│   ├── services/             # API client
│   └── utils/                # Frontend utilities
│
├── 📂 views/                 # Page components
│   ├── Dashboard.tsx         # Main user dashboard
│   ├── Transfer.tsx          # Money transfers
│   ├── Cards.tsx             # Card management
│   ├── Loans.tsx             # Loan services
│   ├── Analytics.tsx         # Spending analytics
│   ├── Support.tsx           # Help & support
│   ├── Admin*.tsx            # Admin panel views
│   └── ...
│
├── 📂 model/                 # ML models & API
│   ├── ml_api.py             # Flask ML server
│   ├── *.pkl                 # Trained models
│   └── requirements.txt      # Python dependencies
│
├── 📂 database/              # SQL scripts
│   ├── schema.sql            # Database schema
│   ├── seed.sql              # Sample data
│   └── migrations/           # Schema updates
│
├── 📂 components/            # Shared components
├── 📂 docs/                  # Documentation
├── App.tsx                   # Main React app
├── types.ts                  # TypeScript types
└── package.json              # Dependencies
```

---

## 🔐 Security Features

| Feature | Implementation |
|---------|----------------|
| 🔑 **Authentication** | JWT access + refresh tokens |
| 🔒 **Password Security** | bcrypt with 12 salt rounds |
| 🚫 **Rate Limiting** | Request throttling on sensitive endpoints |
| ✅ **Input Validation** | Zod schemas on all inputs |
| 💼 **Double-Entry Ledger** | Ensures financial data integrity |
| 🔄 **Idempotency** | Prevents duplicate transactions |
| 🛡️ **CORS Protection** | Restricted origin access |
| 🍪 **Secure Cookies** | HttpOnly cookies for tokens |

---

## 📸 Screenshots

### Customer Dashboard
> Modern dashboard with real-time balance, spending charts, and fraud alerts

### Admin Panel
> Comprehensive admin tools for managing users, loans, and system settings

### 3D Login Experience
> Immersive Three.js powered authentication page

### AI Chat Support
> Intelligent chatbot with live web search capabilities

---

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

---

<div align="center">

**⭐ Star this repository if you find it helpful!**

Made with ❤️ for the developer community

</div>
