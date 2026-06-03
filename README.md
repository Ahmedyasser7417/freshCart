# FreshCart - Angular E-commerce Platform

[![Angular](https://img.shields.io/badge/Angular-17-red.svg)](https://angular.io/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue.svg)](https://www.typescriptlang.org/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple.svg)](https://getbootstrap.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE.md)

## 📌 Overview

FreshCart is a robust and fully-featured e-commerce web application built with Angular 17, featuring server-side rendering (SSR) for optimal performance and SEO. It provides a seamless shopping experience with support for multiple languages, comprehensive user authentication, product browsing, cart management, and secure checkout.

## 🌟 Live Demo

🚀 [![Live Demo](https://img.shields.io/badge/Demo-Live-blue?logo=vercel)](https://fresh-cart-nine-jet.vercel.app/)
Explore the full functionality of the app directly in your browser.

## 📸 Screenshots

|        Screenshot 1        |        Screenshot 2        |
| :------------------------: | :------------------------: |
| ![11](/screenshots/11.png) | ![12](/screenshots/12.png) |
|  ![1](/screenshots/1.png)  |  ![2](/screenshots/2.png)  |
|  ![3](/screenshots/3.png)  |  ![4](/screenshots/4.png)  |
|  ![8](/screenshots/8.png)  | ![10](/screenshots/10.png) |

## 🚀 Features

### 🌐 Internationalization (i18n)

- Supports both English and Arabic languages.
- Automatically adjusts text direction (RTL/LTR).

### 🔒 Authentication

- Secure user registration and login.
- Password reset functionality with email verification.
- JWT token-based authentication.

### 🛒 Product Management

- Browse and filter products, categories, and brands.
- Detailed product pages with ratings and image galleries.
- Advanced pagination and search capabilities.

### 📦 Shopping Cart

- Add, remove, update product quantities dynamically.
- Real-time cart updates and persistent cart state.

### 📑 Order Processing

- Checkout process with secure payment integration.
- Order history and status tracking.

### 🎨 Dynamic UI & UX

- Responsive design compatible with all devices.
- Interactive notifications and loading indicators.
- Dark mode support.

### 🧩 Modular Architecture

- Standalone components using Angular 17.
- Clear separation of concerns via services and guards.

### 🧪 Testing

- Comprehensive unit tests with Jasmine.
- Fully tested components and services.

### 🔧 Developer Tools

- Angular Signals for reactive state management.
- Interceptors for error handling, loading states, and token management.

---

## 🛠️ Technologies Used

| Category                 | Technologies                              |
| ------------------------ | ----------------------------------------- |
| **Frontend**             | Angular 17, TypeScript, SCSS, Bootstrap 5 |
| **Backend (SSR)**        | Express.js with Angular Universal         |
| **State Management**     | Angular Signals                           |
| **Testing**              | Jasmine, Karma                            |
| **Notifications**        | ngx-toastr, SweetAlert2                   |
| **Loading Indicators**   | ngx-spinner                               |
| **Internationalization** | ngx-translate                             |
| **Build Tools**          | Angular CLI, Webpack                      |

---

---

## 📁 Project Structure

```
The following shows the core folder and file organization of the project.

src/
├── app/
│   ├── components/
│   │   ├── products/
│   │   ├── categories/
│   │   ├── cart/
│   │   ├── auth/
│   │   ├── orders/
│   │   └── navigation/
│   ├── services/
│   │   ├── auth.service.ts
│   │   ├── products.service.ts
│   │   ├── cart.service.ts
│   │   ├── categories.service.ts
│   │   ├── orders.service.ts
│   │   └── translate.service.ts
│   ├── guards/
│   │   ├── auth.guard.ts
│   │   └── logged-in.guard.ts
│   ├── interceptors/
│   │   ├── headers.interceptor.ts
│   │   ├── errors.interceptor.ts
│   │   └── loading.interceptor.ts
│   ├── pipes/
│   │   ├── search.pipe.ts
│   │   └── trim-text.pipe.ts
│   ├── interfaces/
│   │   ├── product.interface.ts
│   │   ├── user.interface.ts
│   │   └── order.interface.ts
│   └── app.component.ts
├── assets/
│   ├── images/
│   ├── i18n/
│   │   ├── en.json
│   │   └── ar.json
│   └── screenshots/
├── environments/
│   ├── environment.ts
│   └── environment.prod.ts
├── styles.scss
├── angular.json
├── server.ts
└── package.json
```

---

## 🚦 Installation & Setup

Follow these steps to install dependencies and run the app locally or in production.

### Prerequisites

- Node.js (v18+ recommended)
- Angular CLI (v17+)

### Installation

```bash
git clone https://github.com/ahmedgaafer1/ecommerce.git
cd ecommerce
npm install
```

### Development Server

```bash
npm run dev:ssr
```

### Production Build

```bash
npm run build:ssr
npm run serve:ssr
```

---

## 🧑‍💻 Author

- **Ahmed Yasser**\
  [GitHub](https://github.com/Ahmedyasser7417) | [LinkedIn](https://linkedin.com/in/ahmedyasser2222)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
