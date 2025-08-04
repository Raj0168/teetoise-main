# Teetoise – Full Stack E-commerce Platform

Teetoise is a full-stack e-commerce platform built for a clothing brand. It features secure payment processing, real-time order tracking, an admin dashboard for product and order management, and integrations with logistics and notification services.

---

### Quick Links

- Main Repository: [teetoise-main](https://github.com/Raj0168/teetoise-main)
- Frontend Repo: [teetoise-frontend](https://github.com/Raj0168/teetoise-frontend)
- Backend Repo: [teetoise-backend](https://github.com/Raj0168/teetoise-backend)
- GitHub Project Board: [Teetoise – Project Board](https://github.com/users/Raj0168/projects/2)

---

![React](https://img.shields.io/badge/frontend-React-blue)
![Node.js](https://img.shields.io/badge/backend-Node.js-green)
![GitHub Project](https://img.shields.io/badge/project-board-informational)
![License](https://img.shields.io/github/license/Raj0168/teetoise-main)

---

## Preview

All screenshots are taken from the live version of the application before it was taken offline. The application was fully responsive and production-ready.

### Login Page

User login screen with email/password.  
<img src="public/screenshots/0.Login.webp" alt="Login Page" width="150" />

### Register Page

User registration screen with input validation and OTP verification using mail.  
<img src="public/screenshots/0.Register.webp" alt="Register Page" width="150" />

### Home Page – Banner and Promotions

Landing page with promotional banners, featured collections, categories, blogs.
<br/>
<img src="public/screenshots/1.Home_1.webp" alt="Home Banner" width="150" />

### Home Page – Featured Products

More on Home screen.  
<img src="public/screenshots/2.Home_2.webp" alt="Featured Products" width="150" />

### Sidebar Navigation

Accessible sidebar menu optimized for mobile users.  
<img src="public/screenshots/3.Sidebar.webp" alt="Sidebar Navigation" width="150" />

### Product Overview

Grid layout of product listings with filters.  
<img src="public/screenshots/4.Product_overview.webp" alt="Product Grid" width="150" />

### Product Details Page

Detailed product information with image gallery and color, size options.  
<img src="public/screenshots/5.Product_details.webp" alt="Product Details" width="150" />

### Product Filters

Category, price range, and size filters.  
<img src="public/screenshots/5.Product_filters.webp" alt="Product Filters" width="150" />

### More Product details

Product manufacturer and quality details.  
<img src="public/screenshots/6.Product_details_2.webp" alt="Product Detail Variant" width="150" />

### Wishlist Page

View and manage all saved products.  
<img src="public/screenshots/7.Product_wishlists.webp" alt="Wishlist" width="150" />

### Cart Page

Interactive cart with quantity, variant, and size management.  
<img src="public/screenshots/8.Product_carts.webp" alt="Cart Page" width="150" />

### Checkout Page

Delivery address input and summary before payment.  
<img src="public/screenshots/9.Checkout.webp" alt="Checkout Page" width="150" />

### Payment Gateway

Razorpay integration for secure transactions.  
<img src="public/screenshots/10.Payment.webp" alt="Payment Screen" width="150" />

### Orders Overview

List of all past orders.  
<img src="public/screenshots/11.Orders_overview.webp" alt="Orders Overview" width="150" />

### Order Details Page

In-depth view with delivery status and item breakdown.  
<img src="public/screenshots/12.Order_details.webp" alt="Order Details" width="150" />

### User Account Details

Profile settings and address management.  
<img src="public/screenshots/13.User_details.webp" alt="User Profile" width="150" />

### About Us

Static page with brand mission and story.  
<img src="public/screenshots/14.About_Us.webp" alt="About Us Page" width="150" />

### FAQs

Frequently asked questions section.  
<img src="public/screenshots/15.FAQs.webp" alt="FAQs" width="150" />

---

## Features

- Authentication & Authorization
  - Email/password and Google OAuth login
  - OTP-based verification
  - JWT-based sessions (access/refresh)
  - Password reset and update
- User Management
  - Add/view/delete profile and addresses
- Product Management
  - CRUD operations with admin role
  - Tagging, sizes, colors, variants
  - Trending, new arrivals, recommendations
- Cart & Wishlist
  - Add/remove/update items
  - Size checks and personalized lists
- Orders & Checkout
  - Order placement, tracking, returns, refunds
- Payment Integration
  - Razorpay gateway and token-authenticated endpoints
- Home Content
  - Dynamic admin-editable banners and categories
- Blog
  - Public and admin blog post management

---

## Tech Stack

| Category     | Tech                                 |
| ------------ | ------------------------------------ |
| Frontend     | React, CRA, Material UI, SCSS, Redux |
| Backend      | Node.js, Express, PostgreSQL         |
| DevOps/Infra | AWS EC2, Amplify                     |
| Project Mgmt | GitHub Projects                      |

---

## Local Setup

### Frontend

```bash
git clone https://github.com/Raj0168/teetoise-frontend
cd teetoise-frontend
npm install
npm run dev
```

### Backend

```bash
git clone https://github.com/Raj0168/teetoise-backend
cd teetoise-backend
npm install
npm run dev
```

Make sure you configure your `.env` file for backend and frontend. Refer to each repo’s README for specific environment variables.

---

## Project Management Workflow

All features were organized and tracked using the [GitHub Project Board](https://github.com/users/Raj0168/projects/2).  
Tasks such as `Frontend Development`, `Backend Development`, and `DevOps & Infrastructure` were completed with clean separation and progress tracking.

---

## Author

Created by [Raj0168](https://github.com/Raj0168).  
For more projects and contact details, check out my GitHub profile.

---

## License

This project is licensed under the MIT License.
