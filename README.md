# 🛒 Laravel E-Commerce Project

A simple and responsive E-Commerce Product Management system built using **Laravel** and **MySQL**.

---

## ✨ Features

- Add, Edit, Delete Products
- View Product Listings
- Laravel MVC Architecture
- MySQL Database Integration
- Clean, Responsive Design (Bootstrap)
- Home Page + Product Dashboard

---

## 📁 Folder Structure

/ecommerce_project
├── app/
├── resources/
│ └── views/
│ ├── home.blade.php
│ └── products/
│ ├── index.blade.php
│ ├── create.blade.php
│ └── edit.blade.php
├── routes/
│ └── web.php
├── public/
├── database/
│ └── migrations/
│ └── create_products_table.php
└── README.md

---

## ⚙️ How to Run the Project

> Follow these steps to run the Laravel project on your local system.

1. ✅ **Start XAMPP** (Apache + MySQL)

2. ✅ **Create a new database** in phpMyAdmin:  


3. ✅ **Import the SQL File**  
- Go to **phpMyAdmin → ecommerce_project → Import**
- Choose the file: `ecommerce_project.sql`  
- Click **Go**

4. ✅ **Open Terminal and Navigate to Project Folder**
```bash
cd C:\xampp\htdocs\ecommerce_project

php artisan serve

http://127.0.0.1:8000

Admin Info (if required)
No login system added.

Direct access to create, edit, delete products.


Database File
The file ecommerce_project.sql is provided in the repository to create the necessary products table.

Project by Ankita Goyal
Submission for Web Developer Laravel Assignment
🔗 GitHub Repository Link

