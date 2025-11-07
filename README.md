# ☕ CoffeeShop Cashiering System

A **web-based Point of Sale (POS)** system built to streamline **coffee shop orders, billing, and inventory management**.  
This project automates manual cashiering tasks, improves transaction speed, and ensures accurate billing.

## 🧠 Project Overview
The CoffeeShop Cashiering System is designed to help small cafés or coffee shops efficiently manage:
- Product listings and categories  
- Sales and billing operations  
- Real-time order tracking and inventory updates  

It features a clean admin dashboard where the cashier or manager can add items, track sales, and view performance insights.

## 🌟 Features

✅ **Admin Dashboard** – Central control for categories, products, and sales  
✅ **Product Management** – Add, edit, delete, and view product items  
✅ **Category Management** – Organize items under coffee, snacks, etc.  
✅ **Sales Management** – Create and track each transaction in real time  
✅ **Automated Billing** – Calculates total amounts instantly  
✅ **Inventory Control** – Updates stock quantities after each sale  
✅ **Authentication System** – Secure admin login using PHP sessions  
✅ **Database Integration** – MySQL database for structured storage  
✅ **Responsive Design** – Clean UI built with Bootstrap  

## 🧩 Tech Stack

**Frontend:**  
🧱 HTML5, CSS3, JavaScript, Bootstrap  

**Backend:**  
⚙️ PHP (Core PHP), MySQL (phpMyAdmin)  

**Server Environment:**  
🖥️ Apache via XAMPP  

**Architecture:**  
📦 MVC-style structure with Object-Oriented PHP  

## 🗂️ Project Structure

    CoffeeShop-Cashiering-System/
    ├── cscs/
    │   ├── admin/          # Admin panel (dashboard, categories, products, sales)
    │   ├── assets/         # CSS, JS, and media files
    │   ├── classes/        # PHP classes (DB connection, settings)
    │   ├── database/       # Database backup (.sql file)
    │   ├── inc/            # Reusable includes (headers, navigation, etc.)
    │   ├── plugins/        # JS/CSS libraries (toastr, sweetalert, etc.)
    │   ├── uploads/        # Product and banner images
    │   ├── config.php      # Main configuration file
    │   ├── initialize.php  # Project constants and base URL
    │   └── index.php       # Entry point (redirects to admin dashboard)
    └── README.md

## ⚙️ Installation / Setup Instructions

### 1️⃣ Install XAMPP
- Download from: [https://www.apachefriends.org/download.html](https://www.apachefriends.org/download.html)
- Start **Apache** and **MySQL** modules

### 2️⃣ Setup the Project Folder
- Copy this project folder `cscs` into:
      C:\xampp\htdocs\
- Folder path should look like:
      C:\xampp\htdocs\cscs\

### 3️⃣ Import the Database
- Open your browser → go to `http://localhost/phpmyadmin/`
- Create a new database named: `cscs_db`
- Click **Import** → choose the file:
      cscs/database/cscs_db.sql
- Click **Go**

### 4️⃣ Run the Project
Open your browser and go to:
      http://localhost/cscs/

### 5️⃣ Admin Login Credentials
- **Username:** `admin`  
- **Password:** `admin123`

## 🧾 Results / Outcome

🚀 The system allows the coffee shop to:
- Handle customer orders quickly and accurately  
- Auto-generate total bills and update stock in real-time  
- Reduce manual errors and speed up checkout time  
- Maintain all transaction records digitally  

📊 The dashboard provides insights on total categories, products, and sales.

## 🧑‍💻 Developer

**Moulya M C**  

⭐ **If you like this project, give it a star on GitHub!**
