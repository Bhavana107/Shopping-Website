# 🛍️ Smart Shopping Website

A modern and responsive **e-commerce shopping website** built using **React.js, Vite, and Express.js**. The project demonstrates important concepts of React development including reusable components, state management, props, React Hooks, Context API, client-side routing, dynamic routes, REST APIs, and responsive UI design.

The application allows users to browse products, search and filter products, view product details, manage their cart, maintain a wishlist, and complete a simulated checkout process.

---

## 📌 Project Overview

The Smart Shopping Website is designed as a frontend-focused e-commerce application with an Express.js backend.

The project demonstrates how a real-world shopping application can be structured using reusable React components and centralized state management.

### Main Features

- 🛒 Product browsing
- 🔍 Product search
- 🏷️ Category filtering
- 💰 Price filtering
- 📦 Product detail pages
- ❤️ Wishlist management
- ➕ Add products to cart
- 🔄 Update cart quantities
- 🗑️ Remove products from cart
- 🧾 Cart total calculation
- 🚚 Delivery information
- 💳 Simulated checkout
- ✅ Order confirmation
- 🔔 Toast notifications
- 📱 Responsive user interface
- 🌐 Express.js REST APIs

---

## 🎯 Project Objectives

The main objectives of this project are:

1. To develop a responsive e-commerce interface using React.js.
2. To understand component-based architecture.
3. To implement reusable functional and class components.
4. To understand React state management using Hooks and Context API.
5. To implement client-side routing using React Router.
6. To implement dynamic product routes.
7. To handle cart and wishlist operations.
8. To implement product searching and filtering.
9. To develop REST APIs using Express.js.
10. To understand frontend-backend communication.
11. To build a foundation that can later be extended with a database, authentication, payment gateway, and persistent storage.

---

## 🛠️ Technologies Used

### Frontend

- **React.js**
- **JavaScript (ES6+)**
- **Vite**
- **HTML5**
- **CSS3**
- **JSX**
- **React Hooks**
- **React Router**
- **Context API**

### Backend

- **Node.js**
- **Express.js**
- **REST APIs**
- **In-memory data storage**

### Libraries

- **Lucide React** - Icons
- **React Toastify** - Toast notifications

### Development Tools

- **Visual Studio Code**
- **Git**
- **GitHub**
- **npm**

---

## 🏗️ Project Structure

```text
Shopping-Website/
│
├── public/
│
├── src/
│   ├── assets/
│   │
│   ├── components/
│   │   ├── Navbar/
│   │   ├── Product/
│   │   ├── ProductList/
│   │   ├── Cart/
│   │   └── ...
│   │
│   ├── context/
│   │   └── CartContext.jsx
│   │
│   ├── data/
│   │   └── product.js
│   │
│   ├── pages/
│   │   ├── ProductList.jsx
│   │   ├── ProductDetail.jsx
│   │   ├── Wishlist.jsx
│   │   ├── Cart.jsx
│   │   ├── Checkout.jsx
│   │   └── OrderConfirmation.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── ...
│
├── server.js
├── package.json
├── package-lock.json
├── vite.config.js
├── eslint.config.js
└── README.md
