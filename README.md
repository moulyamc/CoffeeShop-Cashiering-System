# CoffeeShop Cashiering System

A simple and fully functional PHP & MySQL-based cashiering system designed for managing categories, products, and sales in a coffee shop.  
Developed as part of a DBMS Mini Project (2023–24).

## 🖥️ Features
- Admin login and authentication
- Manage product categories
- Manage product details
- Dashboard with real-time data
- CRUD operations for all entities
- User-friendly interface

## ⚙️ Installation (XAMPP/WAMP)
1. **Download or clone this repository** into your `htdocs` folder (for XAMPP):  
   ```bash
   C:\xampp\htdocs\CoffeeShop-Cashiering-System
   ```

2. **Create the database**
   - Open **phpMyAdmin**
   - Create a new database named: `cscs_db`
   - Import the SQL file located at:
     ```
     database/cscs_db.sql
     ```

3. **Run the project**
   - Start Apache and MySQL in XAMPP
   - Open your browser and go to:
     ```
     http://localhost/cscs/
     ```

4. **Admin Login**
   - **Username:** `admin`
   - **Password:** `admin123`

## 🗂️ Project Structure
```
CoffeeShop-Cashiering-System/
├── cscs/
│   ├── admin/          # Admin dashboard files
│   ├── classes/        # Database and system classes
│   ├── config.php      # Configuration file
│   ├── initialize.php  # Core constants and database info
│   ├── index.php       # Entry point (redirects to admin)
│   └── ... (other PHP files)
├── database/
│   └── cscs_db.sql     # SQL database file
└── README.md
```

## 🧾 Notes
- Default timezone is set to `Asia/Manila` in `config.php` (you can change if needed)
- Tested with **PHP 8.0+** and **MySQL 10.4+**
- Works on **localhost** using **XAMPP or WAMP**

---
✅ Verified and ready for GitHub upload.
