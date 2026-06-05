# 💳 Wallex — AI-Powered Student Finance Manager

<div align="center">

### Intelligent Financial Management for Students, Powered by Generative AI

*Built with React, Node.js, MongoDB & Google Gemini*

![React](https://img.shields.io/badge/React-18-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-Strict-blue)
![Node.js](https://img.shields.io/badge/Node.js-18+-green)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-success)
![Gemini](https://img.shields.io/badge/Google-Gemini-orange)
![Vitest](https://img.shields.io/badge/Tested-With%20Vitest-yellow)

[🚀 Live Demo](https://wallex-opal.vercel.app)

</div>

---

## 📖 Overview

**Wallex** is a next-generation, AI-powered financial management platform designed specifically for college students.

Unlike conventional budgeting applications, Wallex leverages **Google Gemini's Generative AI capabilities** to automatically understand, classify, and categorize financial transactions with remarkable accuracy.

Built using modern enterprise engineering practices, the platform combines:

* 🤖 AI-driven transaction intelligence
* 🔒 Enterprise-grade authentication & security
* 📊 Smart spending analytics
* 📱 Mobile-first premium user experience
* 🧪 Test-driven development architecture

---

# ✨ Enterprise Highlights

## 🤖 Generative AI Transaction Intelligence

Integrated Google Gemini directly into the backend service layer, replacing traditional ML pipelines with a lightweight AI microservice architecture.

### Key Benefits

* Automatic transaction categorization
* Natural language understanding
* Intelligent spending classification
* ~400ms average classification latency
* Zero model training overhead

---

## ⚡ Custom Data Fetching Architecture

Built a production-style global state abstraction layer through a custom `useApi()` hook.

### Features

* Centralized API management
* Global loading states
* Unified error handling
* Request lifecycle management
* Eliminates repetitive `useEffect()` patterns

This architecture mimics the developer experience of tools such as **React Query** and **SWR** while remaining lightweight and fully customizable.

---

## 🔒 Zero-Trust Authentication System

Designed a secure authentication flow centered around **HttpOnly Cookies**.

### Security Measures

✔ No JWTs stored in localStorage

✔ Protection against XSS attacks

✔ Axios credential interception

✔ Secure cookie transport

✔ Backend cookie validation middleware

### Security Stack

```text
Client
   ↓
HttpOnly Cookie
   ↓
Axios withCredentials
   ↓
Express Middleware
   ↓
Protected Routes
```

---

## 📐 Strict Type-Safe Domain Modeling

Maintained complete type consistency between frontend and backend systems.

### Architecture

```text
MongoDB Schema
      ↓
Mongoose Models
      ↓
TypeScript Interfaces
      ↓
React Components
```

Benefits:

* Zero type drift
* Improved maintainability
* Better IDE support
* Compile-time safety

---

## 🧪 Automated Testing Infrastructure

Implemented a testing framework using:

* Vitest
* jsdom
* React Testing Library

### Coverage

* Financial calculations
* Charting algorithms
* Edge-case handling
* Divide-by-zero protection
* Floating-point precision validation

---

## 🎨 Premium Mobile-First UI/UX

Crafted a highly interactive interface inspired by modern iOS applications.

### Design Features

* Floating bottom navigation
* Glassmorphism effects
* Bento-grid dashboards
* Framer Motion animations
* Hardware-accelerated transitions
* Responsive mobile-first layouts

---

# 🏗️ System Architecture

```text
┌─────────────────────────┐
│      React Frontend     │
│  TypeScript + Vite      │
└──────────┬──────────────┘
           │
           ▼
┌─────────────────────────┐
│     Express Backend     │
│      Node.js API        │
└──────┬─────────┬────────┘
       │         │
       ▼         ▼
┌──────────┐ ┌──────────┐
│ MongoDB  │ │ Gemini AI│
│ Database │ │ Service  │
└──────────┘ └──────────┘
```

---

# 🛠️ Tech Stack

## Frontend

| Technology    | Purpose      |
| ------------- | ------------ |
| React 18      | UI Framework |
| TypeScript    | Type Safety  |
| Vite          | Build Tool   |
| Tailwind CSS  | Styling      |
| Framer Motion | Animations   |
| Vitest        | Testing      |

---

## Backend

| Technology    | Purpose       |
| ------------- | ------------- |
| Node.js       | Runtime       |
| Express.js    | API Layer     |
| MongoDB Atlas | Database      |
| Mongoose      | ODM           |
| Zod           | Validation    |
| Google Gemini | AI Processing |

---

# 🎯 Core Features

### Smart Expense Tracking

* AI-powered transaction categorization
* Automated spending insights
* Dynamic expense breakdowns

### Financial Analytics

* Spending trends
* Category-wise analysis
* Budget tracking

### Student-Focused Experience

* Allowance management
* Parent-linked profiles
* Spending optimization alerts

### AI Recommendations

* Personalized financial insights
* Spending improvement suggestions
* Intelligent categorization engine

---

# 🌐 Live Application

### Demo URL

```bash
https://wallex-opal.vercel.app
```

---

# 👤 Demo Accounts

### Universal OTP

```bash
123456
```

| User                                            | Profile Type             |
| ----------------------------------------------- | ------------------------ |
| [aisha@example.com](mailto:aisha@example.com)   | High Earner Profile      |
| [meera@example.com](mailto:meera@example.com)   | Budget Conscious Profile |
| [farida@example.com](mailto:farida@example.com) | Parent Portal View       |

---

# 🚀 Local Development

## 1️⃣ Clone Repository

```bash
git clone https://github.com/utsavukani/wallex.git
```

---

## 2️⃣ Backend Setup

```bash
cd wallex/backend
npm install
```

Create a `.env` file:

```env
MONGODB_URI=mongodb://localhost:27017/wallex
JWT_SECRET=development_secret_key_123
GEMINI_API_KEY=your_gemini_api_key_here
PORT=3001
CORS_ORIGIN=http://localhost:5173
```

Run Backend:

```bash
npm start
```

---

## 3️⃣ Frontend Setup

```bash
cd wallex/Frontend
npm install
npm run dev
```

Application available at:

```bash
http://localhost:5173
```

---

# 🔐 Security Hardening

### Authentication

* HttpOnly Cookies
* Secure JWT Transport
* Session Validation Middleware

### API Protection

* Helmet.js Security Headers
* Strict CORS Policies
* Origin Whitelisting

### Data Validation

* Zod Runtime Validation
* Schema Enforcement
* Malformed Request Protection

---

# 📈 Engineering Principles

* Test-Driven Development (TDD)
* Stateless Service Architecture
* Strict Type Safety
* Mobile-First Design
* Security-First Development
* Component Reusability
* Clean Architecture Patterns

---

# 📝 License

Distributed under the **MIT License**.

---

<div align="center">

### Built to demonstrate enterprise-scale full-stack engineering, AI integration, and modern product development practices.

⭐ If you found this project interesting, consider giving it a star.

</div>
