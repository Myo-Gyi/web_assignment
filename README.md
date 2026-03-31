# HninYmo Jewellery Shop

A full-stack jewellery shop web application with appointment booking, product browsing, shopping cart, and admin dashboard.

## Tech Stack

**Frontend:** React, Vite, Material UI, Tailwind CSS, React Router  
**Backend:** Express, Sequelize, MySQL, JWT Authentication, Multer

## Project Structure

```
├── frontend/    # React client app
├── backend/     # Express API server
└── package.json # Root scripts
```

## Getting Started

### Prerequisites

- Node.js
- MySQL

### Installation

1. Install dependencies
   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```

2. Configure environment variables  
   Create `backend/.env` with your database credentials:
   ```
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=your_password
   DB_NAME=your_database
   JWT_SECRET=your_secret
   ```

3. Seed the database
   ```bash
   cd backend && npm run seed
   ```

4. Run the application
   ```bash
   # From the root directory
   npm run dev:server   # Start backend
   npm run dev:client   # Start frontend
   ```

## Features

- Product browsing and search
- Shopping cart and checkout
- User authentication (register/login)
- Appointment booking for jewellery services
- Order management
- Admin dashboard (products, orders, appointments, reports)
