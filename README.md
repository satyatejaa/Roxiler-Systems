# FullStack Store Rating Platform

A full-stack web application that allows users to sign up, log in, browse stores, submit ratings (1–5), and update their ratings.  
Includes **role-based access** for Admins, Store Owners, and Normal Users.

---

## 🛠 Tech Stack

**Frontend:** React (React Router, Fetch API)  
**Backend:** Express.js (Node.js) + Sequelize ORM  
**Database:** PostgreSQL  
**Auth:** JWT-based Authentication  
**Containerization:** Docker + docker-compose

---

## ✨ Features

### 🔑 Authentication & Authorization
- JWT-based login system for all users.
- Role-based access control:
  - **Admin**: Manage users & stores, view dashboard metrics.
  - **Normal User**: Sign up, search stores, submit/edit ratings.
  - **Store Owner**: View store ratings and user feedback.

### 🧑‍💻 Admin Functionalities
- Add new users (Admin, Store Owner, Normal).
- Add new stores.
- View dashboard with:
  - Total Users
  - Total Stores
  - Total Ratings
- View & filter lists of:
  - Users (Name, Email, Address, Role)
  - Stores (Name, Email, Address, Rating)

### 👤 Normal User Functionalities
- Sign up & log in.
- Update password.
- View all stores with search filters (Name, Address).
- Submit and modify store ratings (1–5).

### 🏪 Store Owner Functionalities
- Log in and update password.
- View list of users who rated their store.
- View average rating for their store.

### ✅ Validations
- **Name:** 20–60 characters  
- **Address:** ≤ 400 characters  
- **Password:** 8–16 chars, 1 uppercase, 1 special char  
- **Email:** Standard email format  

---

## 📂 Project Structure

