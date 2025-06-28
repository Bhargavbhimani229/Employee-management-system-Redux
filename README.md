# 🧑‍💼 Employee Management System (EMS) using React + Redux Toolkit

Live Project 👉 [Employee Management System](https://employee-management-system-redux-nine.vercel.app)

## 🚀 Project Overview

The **Employee Management System (EMS)** is a modern web application built using **React**, **Redux Toolkit**, **Bootstrap**, and **LocalStorage** (for authentication and persistence). It provides a complete platform for administrators to manage employees and for employees to access their work-related data.

---

## 🔐 User Roles

- 👑 **Admin Panel**
  - Login via admin credentials
  - Add / delete / update employees
  - Assign tasks and set salary
  - Upload employees via CSV
  - Generate salary slips

- 👤 **Client Panel (Employee)**
  - Login via email
  - View assigned tasks
  - View personal salary slip

---

## 🛠️ Tech Stack

| Tech              | Purpose                        |
|------------------|----------------------------------|
| React + Vite     | Frontend Framework              |
| Redux Toolkit    | Global state management         |
| Bootstrap        | UI Styling                      |
| React Router     | Page Routing                    |
| LocalStorage     | Auth & Data Persistence         |
| PapaParse        | CSV Upload Support              |

---

## 🧩 Features

### ✅ Admin Features:
- Admin login (LocalStorage-based)
- Add / Delete / Edit employees
- Task assignment per employee
- Salary input per employee
- CSV upload for bulk employees
- Printable salary slip generation

### ✅ Employee Features:
- Login using email
- View own task list
- View salary slip
- Secure access (only their data)

---

## 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/Bhargavbhimani229/Employee-management-system-Redux.git

# Navigate to the folder
cd Employee-management-system-Redux

# Install dependencies
npm install

# Start the development server
npm run dev
