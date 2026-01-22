# 🛋️ Modern Furniture E-Commerce Suite

[![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)](https://flutter.dev/)
[![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)](https://expressjs.com/)

> **🔒 Private Repository Showcase**
>
> This repository serves as a visual demonstration of a full-stack e-commerce ecosystem I developed. It includes a **Customer Mobile App**, an **Admin Dashboard**, and a **Custom Node.js Backend**.
> *Source code is available upon request for technical interviews.*

---

## 📱 Client Application (Flutter)

The customer-facing application allows users to browse, search, and purchase furniture with a focus on UI/UX and smooth performance.

### 1. **Onboarding & Authentication** 🔐
*A seamless entry experience featuring secure JWT authentication, social sign-ins (Google/Apple), and password recovery flows.*

<table border="0">
  <tr>
    <td align="center" width="33%">
      <img src="screenshots/splash.png" width="100%" />
      <br><b>Smart Onboarding</b>
    </td>
    <td align="center" width="33%">
      <img src="screenshots/login.png" width="100%" />
      <br><b>Secure Login</b>
    </td>
    <td align="center" width="33%">
      <img src="screenshots/register.png" width="100%" />
      <br><b>Registration</b>
    </td>
  </tr>
</table>

### 2. **Discovery & Product Details** 🛋️
*Advanced filtering and detailed product views. Features include "New Collection" banners, horizontal category scrollers, and rich product imagery.*

<table border="0">
  <tr>
    <td align="center" width="33%">
      <img src="screenshots/home.png" width="100%" />
      <br><b>Home Dashboard</b>
    </td>
    <td align="center" width="33%">
      <img src="screenshots/category.png" width="100%" />
      <br><b>Visual Discovery</b>
    </td>
    <td align="center" width="33%">
      <img src="screenshots/details.png" width="100%" />
      <br><b>Product Specifications</b>
    </td>
  </tr>
</table>

### 3. **Cart & Secure Checkout** 💳
*Complete order lifecycle management. Users can manage cart quantities, select saved addresses, and process payments securely.*

<table border="0">
  <tr>
    <td align="center" width="33%">
      <img src="screenshots/cart.png" width="100%" />
      <br><b>Shopping Cart</b>
    </td>
    <td align="center" width="33%">
      <img src="screenshots/checkout.png" width="100%" />
      <br><b>Order Summary</b>
    </td>
    <td align="center" width="33%">
      <img src="screenshots/payment.png" width="100%" />
      <br><b>Payment Gateway</b>
    </td>
  </tr>
</table>

### 4. **User Profile & Management** ⚙️
*A dedicated hub for users to manage their digital footprint, including shipping addresses, security settings, and order history.*

<table border="0">
  <tr>
    <td align="center" width="33%">
      <img src="screenshots/profile.png" width="100%" />
      <br><b>Profile Hub</b>
    </td>
    <td align="center" width="33%">
      <img src="screenshots/address.png" width="100%" />
      <br><b>Address Book</b>
    </td>
    <td align="center" width="33%">
      <img src="screenshots/settings.png" width="100%" />
      <br><b>App Settings</b>
    </td>
  </tr>
</table>

---

## 💻 Admin Dashboard (Flutter) 📊

A separate Flutter application built for administrators to manage the business logic on the go.

*   **Inventory Control:** Add, update, and delete products with support for variants (size, color).
*   **Order Management:** Track order status (Processing → Shipped → Delivered).
*   **Marketing Tools:** Create and manage discount coupons and promotional banners.
*   **Analytics:** Visual charts displaying sales performance and revenue.

---

## 🔙 Backend API (Node.js) ☁️

The system is powered by a robust REST API built with **Express.js** and **MongoDB**.

### **Key Features:**
*   **🛡️ Security First:** Implemented `Helmet` for headers, `XSS-Clean` for sanitization, and Rate Limiting to prevent brute-force attacks.
*   **🔑 Authorization:** Role-Based Access Control (RBAC) separating `User` and `Admin` privileges.
*   **📦 Advanced Data Models:** Complex schemas handling Categories, Sub-categories, Brands, and Product Variants.
*   **🖼️ Media Handling:** Image upload functionality for product galleries.
*   **🔔 System Notifications:** Integrated notification system for order updates.

---

## 🛠️ Tech Stack Summary

| Domain | Technologies Used |
| :--- | :--- |
| **Mobile (Client & Admin)** | Flutter, Dart, Provider/GetX, Dio, CachedNetworkImage |
| **Backend** | Node.js, Express.js, JWT, Bcrypt.js |
| **Database** | MongoDB, Mongoose ODM |
| **Tools** | Postman, Git, VS Code |

---

### 📬 Contact

If you would like to view the source code or discuss the architecture of this project, please feel free to reach out.

*   **Email:** [Your Email Here]
*   **LinkedIn:** [Your LinkedIn Link Here]
