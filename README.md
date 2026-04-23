# 🛒 E-Commerce Platform

A modern Full-Stack E-Commerce Website built with **Spring Boot 3** and **React**.


https://github.com/user-attachments/assets/c8f39a48-1b21-4a6a-adca-0a65a1eef143


## ✨ Features

| User Features | Admin Features |
|--------------|----------------|
| 🔐 JWT Authentication | 📊 Dashboard & Analytics |
| 🛍️ Product Browsing & Search | 📦 Product Management |
| 🛒 Shopping Cart | 📂 Category Management |
| 📦 Order Tracking | 📋 Order Management |
| ⭐ Reviews & Ratings | 👥 User Management |

## 🛠️ Tech Stack

| Backend | Frontend | Database |
|---------|----------|----------|
| Java 21 | React 18 | MongoDB |
| Spring Boot 3.2 | Vite 5 | |
| Spring Security (JWT) | Tailwind CSS | |
| Spring Data MongoDB | Zustand | |

## 🚀 Quick Start

### Prerequisites
- Java 21, Node.js 18+, MongoDB

### Backend
```bash
cd backend
# Set environment variables in .env file
mvn spring-boot:run
```
Server runs at `http://localhost:8080`

### Frontend
```bash
cd frontend
npm install
npm run dev
```
App runs at `http://localhost:5173`

## ⚙️ Environment Variables

**Backend** (`.env`)
```env
MONGODB_URI=mongodb://localhost:27017/ecommerce
JWT_SECRET=your-secret-key
```

**Frontend** (`.env`)
```env
VITE_API_URL=http://localhost:8080/api
```

## 📄 License


---

MIT License

<p align="center">Built with ❤️ by Ajay Chaudhary</p>
