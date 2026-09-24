# 📚 BookSeller — Full-Stack MERN BookStore Website

A full-stack e-commerce BookStore application built with the MERN stack (MongoDB, Express.js, React.js, Node.js), featuring a customer-facing storefront, secure checkout with Stripe, and a dedicated admin panel for managing products and orders.

## ✨ Features

- 🛍️ Fully responsive BookStore frontend built with React.js & Tailwind CSS
- 🔐 User authentication & authorization (Login/Register)
- 📦 Dynamic product management system (Books CRUD)
- 🛒 Shopping cart & checkout flow
- 💳 Secure payments integration with Stripe
- 🧑‍💼 Admin panel for managing books, orders, and users
- ⚙️ RESTful backend API with Express.js & MongoDB

## 🛠️ Tech Stack

**Frontend:** React.js, Tailwind CSS  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Payments:** Stripe  
**Admin Panel:** React.js

## 📁 Project Structure

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- MongoDB database (local or Atlas)

### Installation

1. Clone the repository
```bash
   git clone https://github.com/Abhishek738642/BookSeller-main.git
```

2. Install dependencies for each part
```bash
   cd backend && npm install
   cd ../frontend && npm install
   cd ../admin && npm install
```

3. Create a `.env` file inside `backend/` with your environment variables (MongoDB URI, Stripe keys, JWT secret, etc.)

4. Run the backend
```bash
   cd backend && npm start
```

5. Run the frontend
```bash
   cd frontend && npm run dev
```

6. Run the admin panel
```bash
   cd admin && npm run dev
```

## 📝 License

This project is for learning purposes.
