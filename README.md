# 💸 Walletify

**Walletify** is a modern full-stack personal finance management system that enables users to **track, organize, and analyze their income and expenses** across web and mobile platforms.

> ⚠️ This repository is a **hub repository**.  
> It contains project overview, documentation, and links to individual service repositories.  
> Source code is maintained in separate repositories for scalability and clean architecture.

---

## 🚀 Overview

Walletify is designed to provide a **simple yet powerful way to manage personal finances**.

Users can:

- Sign up and securely log in
- View a **financial dashboard** with summarized insights
- Track **income and expenses in real-time**
- Organize financial data using **logbooks**
- Access the system seamlessly on **web and Android devices**

---

## ✨ Core Features

### 🔐 Authentication
- Secure user registration and login
- JWT-based authentication

### 📊 Dashboard
- Summary of total income and expenses
- Visual representation of financial activity
- Recent transaction history (income & expenses)

### 📒 Logbooks (Key Feature)
- Create **multiple logbooks** to organize finances
- Each logbook acts as an **isolated financial workspace**

**Use cases:**
- Monthly tracking (e.g., January 2026)
- Project-based expense management
- Personal vs business finance separation

### 💰 Transaction Management
- Add, update, and delete income and expense records
- Structured and categorized financial tracking

### 📱 Mobile-First Experience
- Fully responsive design
- Optimized for mobile usage
- Android wrapper for app-like accessibility

---

## 🏗 Project Architecture

Walletify follows a **multi-repository architecture**, where each component is developed and maintained independently.

| Component | Description | Repository |
|----------|------------|------------|
| 🌐 Frontend | React-based user interface | https://github.com/DilanSriyantha/walletify-frontend.git |
| ⚙️ Backend | NestJS API with Prisma ORM | https://github.com/DilanSriyantha/walletify-backend.git |
| 📱 Android | Mobile wrapper (WebView-based) | https://github.com/DilanSriyantha/walletify-android.git |

---

## 🛠 Tech Stack

**Frontend**
- React.js

**Backend**
- NestJS (Node.js)
- REST API architecture
- JWT Authentication

**Database**
- MySQL
- Prisma ORM

**Mobile**
- Android (WebView-based wrapper)

---

## 📸 Screenshots

<div>
  <img src="https://i.ibb.co/MyHWPBgX/Screenshot-2026-03-29-171109.png" alt="Screenshot 2026 03 29 171109" border="0">
  <img src="https://i.ibb.co/35dFwB2t/Screenshot-2026-03-29-173407.png" alt="Screenshot 2026 03 29 173407" border="0">
  <img src="https://i.ibb.co/mFgw3qq0/Screenshot-2026-03-29-173544.png" alt="Screenshot 2026 03 29 173544" border="0">
  <img src="https://i.ibb.co/TD2pR7Pr/Screenshot-2026-03-29-173557.png" alt="Screenshot 2026 03 29 173557" border="0">
  <img src="https://i.ibb.co/vvXDgxcF/Screenshot-2026-03-29-173618.png" alt="Screenshot 2026 03 29 173618" border="0">
  <img src="https://i.ibb.co/DPDnqV4b/Screenshot-2026-03-29-173640.png" alt="Screenshot 2026 03 29 173640" border="0">
</div>

---

## 🌍 Deployment

- Frontend: https://your-domain.com  
- Backend API: https://api.your-domain.com  
- Hosting: VPS (CyberPanel + OpenLiteSpeed or any other setup you prefer)  
- Database: MySQL  

---

## 🧠 Design Principles

- **Separation of concerns** through multi-repo architecture
- **Scalable backend design**
- **Mobile-first UI/UX**
- **Clean and maintainable codebase**

---

## 🔮 Future Improvements

- Budget planning and alerts
- Advanced analytics and insights
- Multi-currency support
- Cloud sync and backups
- Native mobile application (Flutter / React Native)

---

## 📄 License

MIT License
