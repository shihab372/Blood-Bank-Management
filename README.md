# 🩸 Blood Bank Management System

The **Blood Bank Management System** is a web-based platform designed to facilitate efficient blood donation coordination between users, donors, and administrators. It allows users to act as donors by updating their status, streamlines blood request management, and provides a centralized dashboard for administrators.

---

## 📌 Project Overview

This project is a **Blood Bank Management System** developed to automate and streamline blood donation services. It enables users to find donors, schedule blood requests, and allows registered users to switch to donor mode by updating their profile status.

> 📍 Path to run the project:
> `http://localhost/blood`

---

## 🔹 Key Features

* 🧑‍💻 **Update Profile** – Users can update personal details and choose to act as a donor
* 🩸 **Donor Mode Switching** – Users can become donors by enabling donor status in their profile
* 🗓️ **Request Scheduling** – Users can request blood donations by selecting a date, time, and location
* 🧭 **Find Donor** – Search and filter available donors based on area and blood type
* 📋 **Check Request Status** – Track the status of donation requests in real time
* 🧾 **Admin Panel** – Admins manage users and monitor the system

---

## 🚀 System Modules

| Module             | Description                                                             |
| ------------------ | ----------------------------------------------------------------------- |
| **Authentication** | Secure login and registration system for users, donors, and admins      |
| **User Module**    | Update profile, become a donor, request blood, and check request status |
| **Donor Module**   | Manage donation requests and update donor availability and profile      |
| **Admin Module**   | Manage all users and system operations, and update admin details        |

---

## 🏛 System Architecture

* **Frontend**: HTML, CSS, JavaScript
* **Backend**: PHP (Object-Oriented)
* **Database**: MySQL (Relational Database Model)
* **Security**: Role-Based Access Control (RBAC)

---

## 🛠 Database Setup

❗ **Important:**
🔴 The database file `blood.sql` is included inside the `.zip` project folder.

➡️ Just extract the `.zip`, open **phpMyAdmin**, and **import `blood.sql`** into a new database named `blood_db`.

---

## ▶️ Running the Project

* Start a local server using **XAMPP** or **WAMP**
* Open your browser and go to:

```
http://localhost/blood
```

---

## 👥 User Roles & Functions

### 👤 User

* **Update Profile** – Update your personal information and enable donor mode
* **Find Donor** – Search for available blood donors in your area
* **Check Request** – Monitor the status of your blood donation requests

### 🩸 Donor

* **Manage Requests** – View and respond to blood donation requests
* **Donor Profile** – Edit your availability and donor status

### 🛡️ Admin

* **User Management** – Manage all registered users
* **Admin Profile** – View and update your profile details

---

## ✅ Conclusion

The Blood Bank Management System offers a reliable and user-friendly platform for managing and coordinating blood donations. With smart features like donor switching, automated request tracking, and role-based access, the system helps save lives by making blood donation more organized and accessible.


