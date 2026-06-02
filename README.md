# 💰 PennyPilot – AI Powered Personal Finance Management Platform

Take control of your finances with intelligent expense tracking, budget management, receipt scanning, recurring transaction automation, and AI-powered insights.


## 🚀 Live Demo

🌐 **Try the Application Here**

**Live Demo:**
penny-pilot-psi.vercel.app


# 🌟 Overview

**PennyPilot** is a modern AI-powered personal finance management platform built with **Next.js 15, Prisma, Clerk Authentication, PostgreSQL, Inngest, and Gemini AI**.

The application helps users manage accounts, track expenses, monitor budgets, automate recurring transactions, and gain actionable financial insights through an intuitive dashboard.

Whether you're a student, professional, or business owner, PennyPilot provides everything you need to organize your financial life in one place.



# ✨ Features

## 📊 Smart Financial Dashboard

Get a complete overview of your finances with:

* Account balances
* Income tracking
* Expense tracking
* Recent transactions
* Spending analytics



## 💳 Multi-Account Management

Create and manage multiple accounts:

* Savings Accounts
* Current Accounts
* Personal Accounts
* Business Accounts

Track balances independently while maintaining a unified financial overview.


## 🧾 AI Receipt Scanner

Upload receipts and automatically extract transaction information using AI.

### Automatically Detects:

✔ Amount
✔ Category
✔ Merchant Name
✔ Date
✔ Transaction Details


## 🎯 Budget Management

Set monthly spending limits and monitor progress in real-time.

### Features:

* Budget creation
* Budget tracking
* Spending progress visualization
* Budget alerts


## 🔄 Recurring Transactions

Automate recurring payments and income streams.

Examples:

* Salary
* Rent
* Subscription Payments
* Utility Bills
* EMI Payments


## 📈 Financial Analytics

Interactive charts and reports help users understand:

* Spending patterns
* Income distribution
* Category-wise expenses
* Account performance


## 🔐 Secure Authentication

Powered by **Clerk Authentication**.

Features include:

✔ Sign Up
✔ Sign In
✔ Protected Routes
✔ User Session Management


## 🤖 AI Powered Insights

Leverages Google's Gemini AI to provide intelligent financial assistance and transaction processing.


## 📧 Automated Notifications

Receive automated alerts and reminders for:

* Budget limits
* Important financial updates
* Recurring transactions


## ⚡ Modern User Experience

✔ Responsive Design
✔ Fast Performance
✔ Real-Time Updates
✔ Interactive Charts
✔ Mobile Friendly UI
✔ Beautiful Dashboard


# 🛠 Tech Stack

| Technology   | Purpose                   |
| ------------ | ------------------------- |
| Next.js 15   | Frontend & Backend        |
| React 19     | User Interface            |
| Prisma ORM   | Database Management       |
| PostgreSQL   | Database                  |
| Clerk        | Authentication            |
| Gemini AI    | AI Features               |
| Inngest      | Background Jobs           |
| Tailwind CSS | Styling                   |
| Shadcn UI    | UI Components             |
| Arcjet       | Security & Bot Protection |
| Resend       | Email Services            |


# 🧠 Core Functionalities

### Personal Finance Management

* Income Tracking
* Expense Tracking
* Budget Planning
* Financial Analytics

### AI Features

* Receipt Scanning
* Transaction Extraction
* Smart Categorization

### Automation

* Recurring Transactions
* Budget Monitoring
* Email Notifications


# 📂 Project Structure

```bash
PennyPilot/
│
├── app/
├── actions/
├── components/
├── lib/
├── hooks/
├── prisma/
├── emails/
├── data/
├── middleware.js
├── package.json
├── next.config.mjs
├── README.md
│
├── app/(main)/
│   ├── dashboard/
│   ├── account/
│   └── transaction/
│
└── app/api/
    └── inngest/
```

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/akanshakumari23/PennyPilot.git
```

## 2️⃣ Move Into Project Folder

```bash
cd PennyPilot
```

## 3️⃣ Install Dependencies

```bash
npm install
```

## 4️⃣ Configure Environment Variables

Create a `.env` file and add:

```env
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```

## 5️⃣ Generate Prisma Client

```bash
npx prisma generate
```

## 6️⃣ Run Database Migration

```bash
npx prisma migrate deploy
```

## 7️⃣ Start Development Server

```bash
npm run dev
```


# 📊 Features Included

✔ User Authentication

✔ Dashboard Analytics

✔ Account Management

✔ Budget Tracking

✔ Recurring Transactions

✔ Receipt Scanning

✔ AI Powered Insights

✔ Email Notifications

✔ Responsive Design

✔ Secure Routes

✔ PostgreSQL Database

✔ Prisma ORM


# 🌐 Deployment

This project can be deployed easily on:

✅ Vercel

✅ Railway

✅ Render

✅ DigitalOcean


# 🚀 Future Enhancements

* AI Financial Advisor
* Investment Tracking
* Credit Score Monitoring
* Expense Forecasting
* Mobile Application
* OCR Receipt Improvements
* Multi-Currency Support
* Team Finance Management


# 👩‍💻 Developed By

## Akansha Kumari

💻 Full Stack Developer | AI Enthusiast | Problem Solver

🔗 GitHub:

https://github.com/akanshakumari23


# 🤝 Contributing

Contributions are welcome!

### Steps:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request



# ⭐ Support

If you found this project useful:

⭐ Star this repository

🍴 Fork it

📢 Share it with others

💙 Happy Coding!
