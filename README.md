# 🚀 Task 2 - Basic CRUD Application

![PHP](https://img.shields.io/badge/PHP-8.x-blue?style=for-the-badge\&logo=php)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge\&logo=mysql)
![Git](https://img.shields.io/badge/Git-Version%20Control-red?style=for-the-badge\&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge\&logo=github)

## 📌 Project Overview

This repository contains **Task 2 - Basic CRUD Application** developed as part of the **ApexPlanet Software Pvt. Ltd. Web Development Internship Program**.

The project is a simple blog management system built using **PHP** and **MySQL** that allows users to register, log in, and perform CRUD (Create, Read, Update, Delete) operations on blog posts.

---

## 🎯 Objectives

* Develop a PHP-based CRUD application.
* Implement user registration and login functionality.
* Store and manage blog posts using MySQL.
* Use secure password hashing.
* Implement session management for authenticated users.

---

## 🛠️ Technologies Used

| Technology | Purpose                  |
| ---------- | ------------------------ |
| PHP        | Server-Side Scripting    |
| MySQL      | Database Management      |
| HTML5      | Structure                |
| CSS3       | Styling                  |
| JavaScript | Client-Side Interactions |
| XAMPP      | Local Development Server |
| Git        | Version Control          |
| GitHub     | Repository Hosting       |

---

## 📂 Project Structure

```text
apexplanet-internship/
│
├── index.php
├── README.md
│
├── config/
│   └── database.php
│
├── database/
│   └── blog.sql
│
├── auth/
│   ├── register.php
│   ├── login.php
│   └── logout.php
│
├── posts/
│   ├── create.php
│   ├── read.php
│   ├── edit.php
│   ├── delete.php
│   └── view.php
│
├── includes/
│   ├── header.php
│   ├── footer.php
│   └── navbar.php
│
└── assets/
    ├── css/
    │   └── style.css
    └── js/
        └── script.js
```

---

## ⚙️ Database Setup

### Create Database

```sql
CREATE DATABASE blog;
```

### Create Users Table

```sql
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(100) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL
);
```

### Create Posts Table

```sql
CREATE TABLE posts (
    id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    content TEXT NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

---

## 🔐 Authentication Features

* User Registration
* User Login
* User Logout
* Password Hashing using `password_hash()`
* Password Verification using `password_verify()`
* Session Management

---

## ✨ CRUD Features

### ➕ Create

Add new blog posts through a form.

### 📖 Read

Display all posts stored in the database.

### ✏️ Update

Edit existing blog posts.

### ❌ Delete

Remove unwanted posts from the database.

---

## ▶️ Running the Project

### Step 1

Start Apache and MySQL from XAMPP.

### Step 2

Import the database:

```text
database/blog.sql
```

into phpMyAdmin.

### Step 3

Configure database credentials in:

```php
config/database.php
```

### Step 4

Place the project inside:

```text
xampp/htdocs/
```

### Step 5

Open the browser and visit:

```text
http://localhost/apexplanet-internship/
```

---

## 📸 Features Demonstrated

✅ User Registration

✅ User Login

✅ Secure Password Storage

✅ Session Management

✅ Create Blog Posts

✅ Read Blog Posts

✅ Update Blog Posts

✅ Delete Blog Posts

✅ MySQL Database Integration

---

## 📚 Learning Outcomes

* Understanding CRUD Operations
* Working with PHP and MySQL
* Implementing User Authentication
* Managing Sessions
* Database Design and Integration
* Secure Password Handling

---

## 👨‍💻 Author

**  B. Vaishnav**

B.Tech Student | Web Development Intern

GitHub: https://github.com/Vaishnav2947

LinkedIn: [https://linkedin.com/in/your-profile](https://www.linkedin.com/in/vaishnav-bandari-110477289/)

---

## 📄 Internship

**ApexPlanet Software Pvt. Ltd.**

Web Development Internship (PHP & MySQL)

Task-2: Basic CRUD Application
