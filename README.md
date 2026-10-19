# User Management System (Syntecxhub Internship - Week 2)

A robust RESTful API built with **Node.js**, **Express**, and **MongoDB (Mongoose)** designed for user management, featuring complete CRUD operations and secure HTTP Basic Authentication[cite: 5, 6]. 

This project was developed as part of the **Syntecxhub Web Development Internship Program**.

---

## 🚀 Features
- **CRUD Operations**: Complete functionality to Create, Read, Update, and Delete users[cite: 6].
- **Database Integration**: Built using MongoDB and Mongoose for clean schema definitions and data persistence[cite: 6].
- **Security & Hashing**: Passwords are securely hashed using `bcryptjs`.
- **Authentication**: Endpoints are secured with HTTP **Basic Authentication**[cite: 6].
- **Testing Ready**: Fully tested and compatible with Postman or Python automation scripts[cite: 6].

---

## 🛠️ Tech Stack
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose (supports local MongoDB or In-Memory MongoDB for cloud notebooks)
- **Security**: Bcrypt.js, HTTP Basic Auth

---

## 📌 API Endpoints Overview

| Method | Endpoint | Description | Access |
| :--- | :--- | :--- | :--- |
| **POST** | `/api/users/register` | Register a new user | Public (For initial setup) |
| **GET** | `/api/users` | Retrieve all users (excluding passwords)[cite: 6] | Protected (Basic Auth)[cite: 6] |
| **GET** | `/api/users/:id` | Retrieve a specific user by ID[cite: 6] | Protected (Basic Auth)[cite: 6] |
| **PUT** | `/api/users/:id` | Update user details by ID[cite: 6] | Protected (Basic Auth)[cite: 6] |
| **DELETE** | `/api/users/:id` | Delete a user by ID[cite: 6] | Protected (Basic Auth)[cite: 6] |

---

## ⚙️ Setup & Local Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/Syntecxhub_User_Management_System.git](https://github.com/your-username/Syntecxhub_User_Management_System.git)
   cd Syntecxhub_User_Management_System
