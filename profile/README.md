# 🍽️ ScanCrunch

> **Scan. Browse. Order. Enjoy.**

ScanCrunch is a modern QR-based restaurant ordering platform that enables customers to scan a QR code, browse digital menus, place orders, make secure payments, and track their orders in real time—without waiting for a waiter.

Designed for restaurants, cafés, hotels, food courts, and cloud kitchens, ScanCrunch delivers a seamless, contactless dining experience while helping businesses improve operational efficiency.

---

## 📖 Table of Contents

- Overview
- Features
- System Modules
- Tech Stack
- Architecture
- Project Structure
- Workflow
- Installation
- Environment Variables
- API Overview
- Security
- Deployment
- Future Roadmap
- Contributing
- License

---

# 📌 Overview

Traditional restaurant ordering involves waiting for menus, waiters, and payment processing. ScanCrunch digitizes the complete ordering journey using QR technology.

Customers simply scan a QR code placed on the table to access the restaurant's digital menu. They can customize dishes, place orders instantly, pay online, and receive live order updates while the restaurant and kitchen manage everything through dedicated dashboards.

---

# ✨ Features

## 👤 Customer

- QR Code Menu Access
- Browse Categories
- Search Food
- Food Images
- Item Details
- Ingredients
- Spice Level
- Dietary Information
- Ratings & Reviews
- Add to Cart
- Favorites
- Food Customization
- Coupons & Offers
- Secure Payments
- Cash on Delivery (Optional)
- Live Order Tracking
- Order History
- Notifications
- Dark Mode
- Multi-language Support

---

## 🏨 Restaurant

- Dashboard
- Menu Management
- Category Management
- QR Code Generator
- Order Management
- Inventory Management
- Staff Management
- Customer Reviews
- Coupons
- Analytics
- Sales Reports
- Restaurant Profile

---

## 👨‍🍳 Kitchen

- Live Orders
- Kitchen Dashboard
- Priority Orders
- Cooking Status Updates
- Ready Orders
- Served Orders

---

## 👨‍💼 Admin

- Restaurant Management
- User Management
- Payments
- Reports
- Analytics
- Notifications
- Subscription Plans
- Role Management
- System Settings

---

# 🚀 Benefits

## Customers

- Contactless Ordering
- Faster Service
- Secure Payments
- Better Dining Experience
- Live Order Updates

## Restaurants

- Reduced Manual Errors
- Increased Revenue
- Faster Table Turnover
- Better Customer Experience
- Digital Menu Management
- Analytics Dashboard

---

# 🏗️ System Architecture

```
Customer
      │
      ▼
 QR Code Scan
      │
      ▼
React Frontend
      │
 REST API
      │
      ▼
Spring Boot Backend
      │
      ▼
MySQL Database
      │
      ▼
AWS Cloud Services
```

---

# ⚙️ Tech Stack

## Frontend

- React.js
- React Router
- Tailwind CSS
- Axios
- Redux Toolkit
- React Query
- Framer Motion
- ShadCN UI

---

## Backend

- Spring Boot
- Spring Security
- Spring Data JPA
- JWT Authentication
- REST APIs
- WebSocket
- Maven

---

## Database

- MySQL

---

## DevOps

- Docker
- Kubernetes
- GitHub Actions
- AWS EC2
- AWS RDS
- AWS S3
- AWS CloudFront
- Nginx

---

## Authentication

- JWT
- Refresh Tokens
- Role Based Authentication

---

## Payment Gateway

- Stripe
- Razorpay

---

## Notifications

- Firebase Cloud Messaging

---

# 📂 Repository Structure

```
scancrunch/

├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── README.md
│
├── backend/
│   ├── src/
│   ├── pom.xml
│   └── README.md
│
├── docs/
│
├── docker/
│
├── database/
│
└── README.md
```

---

# 🗂️ Frontend Structure

```
src/

components/

layouts/

pages/

hooks/

services/

store/

routes/

assets/

animations/

styles/

utils/
```

---

# 🗂️ Backend Structure

```
src/main/java/

config/

controller/

service/

repository/

entity/

dto/

mapper/

security/

websocket/

exception/

utils/
```

---

# 🔄 Workflow

```
Customer

↓

Scan QR

↓

Browse Menu

↓

Add to Cart

↓

Checkout

↓

Payment

↓

Restaurant Receives Order

↓

Kitchen Starts Preparing

↓

Order Ready

↓

Served

↓

Order Completed
```

---

# 📱 Screens

- Landing Page
- Restaurant Menu
- Food Details
- Cart
- Checkout
- Payment
- Order Tracking
- Restaurant Dashboard
- Kitchen Dashboard
- Admin Dashboard

---

# 🎨 UI Highlights

- Modern Glassmorphism
- Responsive Design
- Dark Mode
- Smooth Animations
- Skeleton Loading
- Beautiful Charts
- Floating Action Buttons
- Interactive Cards
- Animated Buttons
- Mobile First Design

---

# 📡 API Modules

## Authentication

- Login
- Register
- Refresh Token

---

## Restaurant

- Get Restaurant
- Update Restaurant
- Upload Logo

---

## Menu

- Categories
- Food Items
- Search
- Offers

---

## Orders

- Create Order
- Update Status
- Cancel Order
- Order History

---

## Payments

- Stripe
- Razorpay
- Refunds

---

## Reviews

- Add Review
- View Reviews

---

# 🔒 Security

- JWT Authentication
- HTTPS
- BCrypt Password Encryption
- Role Based Access Control
- Input Validation
- SQL Injection Protection
- CORS Configuration
- Rate Limiting
- Secure Cookies

---

# 🌐 Deployment

## Frontend

- AWS S3
- CloudFront

## Backend

- AWS EC2
- Docker
- Nginx

## Database

- AWS RDS (MySQL)

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/your-org/scancrunch.git
```

---

## Frontend

```bash
cd frontend

npm install

npm run dev
```

---

## Backend

```bash
cd backend

./mvnw spring-boot:run
```

---

# ⚙️ Environment Variables

## Frontend

```env
VITE_API_URL=http://localhost:8080/api

VITE_FIREBASE_KEY=

VITE_STRIPE_KEY=
```

---

## Backend

```env
MYSQL_URL=

MYSQL_USERNAME=

MYSQL_PASSWORD=

JWT_SECRET=

JWT_EXPIRATION=

AWS_ACCESS_KEY=

AWS_SECRET_KEY=

AWS_REGION=

RAZORPAY_KEY=

RAZORPAY_SECRET=
```

---

# 🐳 Docker

Build

```bash
docker-compose build
```

Run

```bash
docker-compose up
```

---

# ☁️ AWS Services

- EC2
- RDS
- S3
- CloudFront
- IAM
- CloudWatch
- Route53
- Certificate Manager

---

# 📈 Future Roadmap

- AI Food Recommendation
- Voice Ordering
- Loyalty Program
- Waiter Calling
- Smart Kitchen Display
- Split Bills
- Subscription Plans
- Delivery Integration
- Restaurant AI Analytics
- QR Table Reservation

---

# 🤝 Contributing

We welcome contributions from everyone.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push branch

```bash
git push origin feature/new-feature
```

5. Create a Pull Request

---

# 👨‍💻 Development Team

| Role | Technology |
|------|------------|
| Frontend | React.js |
| Backend | Spring Boot |
| Database | MySQL |
| DevOps | Docker • Kubernetes • AWS |

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 🌟 Vision

Our vision is to revolutionize restaurant dining by providing a fast, intelligent, secure, and completely digital ordering experience that benefits customers, restaurants, and staff alike.

---

# ❤️ Built With

- React.js
- Spring Boot
- MySQL
- AWS Cloud
- Docker
- Kubernetes
- Tailwind CSS
- Framer Motion

---

<div align="center">

## 🍽️ Scan. Browse. Order. Enjoy.

**Made with ❤️ by the ScanCrunch Team**

</div>
