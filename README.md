# 🩸 Blood Bank Management System – PHP Project

## 📁 Project Type

**Web Application (PHP + MySQL)**

---

## 💡 Project Description

The **Blood Bank Management System** is a PHP-based web application designed to efficiently manage and coordinate blood donations. It supports three roles: **Admin**, **User**, and **Donor** (Users who choose to donate). The system allows users to update their profiles, become donors, submit blood requests, and track status — all while providing administrators with full oversight of the platform.

---

## 🔧 Technologies Used

* **Frontend**: HTML, CSS, JavaScript
* **Backend**: PHP (Object-Oriented)
* **Database**: MySQL
* **Web Server**: Apache (via XAMPP)
* **Security**: Session-based login and Role-Based Access Control (RBAC)

---

## 👥 Roles & Modules

### 👤 User

* Register and log i
* Request blood by selecting **date**, **time**, and **location**
* Search for available donors in their area
* Check the status of their blood donation requests

### 🩸 Donor (via User)
* Update personal profile and choose to become a **donor**
* Users can act as donors by updating their status in their profile
* View and manage incoming donation requests
* Edit donor availability and personal details

### 🛡 Admin

* Secure login with admin credentials
* View, update, and delete any user
* Track and monitor all blood requests
* Edit admin profile details

---

## 📦 Database Overview (`blood.sql`)

The system uses a MySQL database named `blood_db` which includes the following main tables:

| Table Name | Purpose                                                            |
| ---------- | ------------------------------------------------------------------ |
| `user`     | Stores user accounts, profile info, find donor by status               |
| `request`  | Logs blood donation requests with time, date, location, and update status |
| `admin`    | Stores admin login credentials and admin profile info              |

> 🔴 The `blood.sql` file is located inside the project `.zip`. Import it using phpMyAdmin.

---

## ▶️ How to Run the Project

1. **Extract the `.zip` file**
   📁 Place the extracted project folder inside:

   ```
   C:\xampp\htdocs
   ```

2. **Set up the Database**

   * Open **phpMyAdmin**:
     `http://localhost/phpmyadmin`
   * Create a new database named:
     `blood_db`
   * Import the file `blood.sql` included in the zip

3. **Start Your Local Server**

   * Open **XAMPP Control Panel**
   * Start **Apache** and **MySQL**

4. **Access the Application**

   * Open your browser and navigate to:

     ```
     http://localhost/blood
     ```

---

## ✅ Summary

The Blood Bank Management System enables real-time coordination between users and donors, along with admin control for overseeing blood requests. This system provides a reliable digital platform for organizing donation efforts in hospitals, clinics, and communities.


