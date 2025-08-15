# LMS (Learning Management System)

This repository contains the source code and implementation of a Learning Management System (LMS) developed using the **MERN stack** (MongoDB, Express.js, React, Node.js) along with **Tailwind CSS** and **DaisyUI** for styling, **Cloudinary** for managing media, and **Razorpay** for subscription management.

---

## 📚 Table of Contents
- Overview
- Features
- Installation
- Subscription Management
- Prerequisites
- Contributing
- Further Support

---

## 📝 Overview
The Learning Management System (LMS) is a web-based application that facilitates the management and delivery of educational content and training materials. It allows administrators to create courses, manage users, and track progress. Users can access courses, view content, and complete assessments. Additionally, it offers subscription management through Razorpay, allowing users to purchase and cancel subscriptions.

---

## ✨ Features
- User authentication and authorization (using JWT)
- Course creation, modification, and deletion
- Content upload and management via Cloudinary
- User enrollment in courses and progress tracking
- Interactive user interface using React and Tailwind CSS
- Subscription management with Razorpay (for premium content)

---

## 🔑 Admin Login Credentials
**Email:** `jayanthvinaypandillapalli@gmail.com`  
**Password:** `123456789@Lms`

---

## 👤 User Login Credentials
**Email:** `user1@gmail.com`  
**Password:** `123456789@Lms`

---

## ⚙️ Installation

### 1️⃣ Clone the Project
```bash
git clone https://github.com/jayanth422232/Learning-Management-System.git
```

### 2️⃣ Frontend Setup
```bash
cd Client
npm install
npm run dev
```

### 3️⃣ Backend Setup
```bash
cd Server
npm install
npm run dev
```

### 4️⃣ Environment Variables
Create a `.env` file inside the **Server** directory and add:
```
PORT=<Port number>
MONGODB_URL=<Connection_LINK>
JWT_SECRET=<YOUR_LONG_JWT_SECRET>
JWT_EXPIRY=<JWT_EXPIRY>

FRONTEND_URL=<YOUR_FRONTEND_WEBSITE_URL>

CONTACT_US_EMAIL=<YOUR_CONTACT_US_EMAIL>

CLOUDINARY_CLOUD_NAME=<YOUR_CLOUDINARY_CLOUD_NAME>
CLOUDINARY_API_KEY=<YOUR_CLOUDINARY_API_KEY>
CLOUDINARY_API_SECRET=<YOUR_CLOUDINARY_API_SECRET>

SMTP_HOST=<YOUR_SMTP_HOST>
SMTP_PORT=<YOUR_SMTP_PORT>
SMTP_USERNAME=<YOUR_SMTP_USERNAME>
SMTP_PASSWORD=<YOUR_SMTP_PASSWORD>
SMTP_FROM_EMAIL=<YOUR_SMTP_FROM_EMAIL>

RAZORPAY_KEY_ID=<YOUR_RAZORPAY_KEY>
RAZORPAY_SECRET=<YOUR_RAZORPAY_SECRET>
RAZORPAY_PLAN_ID=<YOUR_RAZORPAY_PLAN_ID>
```

---

## 💳 Subscription Management
Users can purchase subscriptions for accessing premium content or features.  
The subscription management interface allows users to:
- View available subscription plans
- Select and purchase a plan via Razorpay
- Cancel an existing subscription

---

## 📊 Low Level Diagram

<img width="2147" height="1021" alt="low-level-diagram" src="https://github.com/user-attachments/assets/f98fb563-1cca-442f-96e2-9ca6332257f5" />

---

## 🛠 Prerequisites
Before running this project locally, ensure you have:
- Node.js (v14.x or higher)
- npm (v6.x or higher)
- MongoDB (v4.x or higher)
- Cloudinary account & API credentials
- Razorpay account & API credentials

---

## 🤝 Contributing
We welcome contributions to the Learning Management System.  
Feel free to create pull requests with your enhancements or bug fixes. Please follow the existing coding style and conventions.

---

## 📩 Further Support
If you encounter any issues or have questions, please raise them in the **GitHub Issues** section, and we’ll be happy to assist you.

---
