# E-Commerce Platform

A modern, full-stack e-commerce platform with an admin dashboard for managing products by category.

## 🎯 Features

- 🛍️ **Product Catalog** - Browse products by category
- 📊 **Admin Dashboard** - Manage products, categories, and orders
- 🛒 **Shopping Cart** - Add/remove products and checkout
- 💳 **Payment Integration** - Secure payment processing
- 👤 **User Authentication** - Secure login and registration
- 📦 **Order Management** - Track and manage orders
- 🔐 **Admin Panel** - Full control over inventory and categories

## 📁 Project Structure

```
e-commerce/
├── frontend/              # React/Vue.js frontend application
│   ├── src/
│   ├── public/
│   └── package.json
├── backend/               # Node.js/Express API
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── package.json
├── dashboard/             # Admin dashboard
│   ├── src/
│   └── package.json
├── database/              # Database configuration
│   ├── migrations/
│   ├── seeds/
│   └── schema.sql
└── docs/                  # Documentation
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+)
- MongoDB or PostgreSQL
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/lailazabareakterkanta-netizen/e-commerce.git
cd e-commerce
```

2. Install dependencies:
```bash
# Frontend
cd frontend && npm install && cd ..

# Backend
cd backend && npm install && cd ..

# Dashboard
cd dashboard && npm install && cd ..
```

3. Configure environment variables:
```bash
# Copy example env files
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env
```

4. Start development servers:
```bash
# Terminal 1 - Backend
cd backend && npm start

# Terminal 2 - Frontend
cd frontend && npm start

# Terminal 3 - Dashboard
cd dashboard && npm start
```

## 🔧 Tech Stack

| Component | Technology |
|-----------|-----------|
| Frontend | React 18 / Vue 3 |
| Backend | Node.js + Express |
| Database | MongoDB / PostgreSQL |
| Dashboard | React Admin Dashboard |
| Authentication | JWT |
| Payment | Stripe / PayPal |

## 📚 Documentation

See the `/docs` folder for detailed documentation on:
- API endpoints
- Database schema
- Setup guides
- Deployment instructions

## 🤝 Contributing

1. Create a feature branch
2. Commit your changes
3. Push to the branch
4. Create a Pull Request

## 📄 License

MIT License - see LICENSE file for details

---

**Created**: 2026-05-10
