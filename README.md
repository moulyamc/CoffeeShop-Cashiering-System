# ☕ CoffeeShop Cashiering System

A **web-based POS (Point of Sale)** system for managing coffee shop orders, billing, and inventory.  
It allows admins to handle products, categories, sales, and reports efficiently — all from a browser interface.

## 🚀 Features

- 🧍 Admin Login & Dashboard  
- 🛒 Manage Products, Categories & Inventory  
- 💵 Process Customer Orders & Billing  
- 📊 View Daily/Monthly Sales Reports  
- 🧾 Receipt Generation  
- 🔐 Secure Authentication System  
- 🕒 Track Transactions with Date & Time Stamps  

## 🧰 Tech Stack

| Category | Technology |
|-----------|-------------|
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Backend | PHP (v8.0+) |
| Database | MySQL (v10.4+) |
| Server | Apache (XAMPP) |

## 📂 Project Structure

```
cscs/
│
├── admin/             # Admin panel files (dashboard, management modules)
├── assets/            # CSS, JS, and image assets
├── build/             # Compiled static assets
├── classes/           # PHP classes for DB and logic handling
├── database/          # SQL files and database configuration
├── dist/              # Distribution files (optional)
├── inc/               # Header, footer, and reusable includes
├── libs/              # Libraries used in the project
├── plugins/           # JS plugins or dependencies
├── uploads/           # Uploaded images or receipts
│
├── 404.html           # Error page
├── config.php         # Database connection configuration
├── index.php          # Main landing page
├── initialize.php     # Initialization file
└── README.md          # Documentation file
```

## ⚙️ Installation / Setup Instructions

1. **Install XAMPP** if you haven’t already.  
   Download from [https://www.apachefriends.org](https://www.apachefriends.org)

2. **Copy the project folder**  
   Place the `cscs` folder inside your XAMPP `htdocs` directory:  
   ```
   C:\xampp\htdocs\cscs
   ```

3. **Start Apache and MySQL**  
   Open XAMPP Control Panel → Start both **Apache** and **MySQL**.

4. **Create Database**
   - Open [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
   - Create a new database named:
     ```
     cscs_db
     ```
   - Import the `.sql` file from the `database` folder.

5. **Run the Project**
   Open your browser and visit:
   ```
   http://localhost/cscs/
   ```

6. **Admin Login**
   - Go to: [http://localhost/cscs/admin/](http://localhost/cscs/admin/)
   - Enter your admin credentials (check your database or setup script for defaults).

## 🧾 Notes

- Default timezone is set to `Asia/Manila` in `config.php` (you can change it if needed).  
- Tested on **PHP 8.0+** and **MySQL 10.4+**.  
- Works perfectly on **localhost** using **XAMPP** (recommended).  
- Folder name must be **cscs** for the URLs and links to work correctly.  

## 🏁 Results

✅ Successfully working Coffee Shop Cashiering System  
🌐 Runs locally on `http://localhost/cscs/`  
📦 All features — Admin, Products, Reports, and Billing — are functioning properly.  

## 👩‍💻 Author

**Moulya MC**  

## ⭐ Support

If you like this project, please consider giving it a **⭐ star on GitHub**  
