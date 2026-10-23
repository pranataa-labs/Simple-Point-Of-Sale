# 🛒 Simple Point Of Sale (POS) Cashier System

![PHP](https://img.shields.io/badge/PHP-8.2%2B-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

A lightweight, reliable desktop-friendly Point-of-Sale (POS) cashier application engineered for retail storefront transactions, inventory stock auditing, customer billing, and daily sales receipts.

---

## ✨ Key Features

- **Cashier Transaction Terminal:** Rapid product lookup, real-time subtotal/tax calculations, and instant change computation.
- **Product & Inventory Management:** Add, edit, and track merchandise inventory with minimum stock thresholds.
- **Transaction Receipt Printing:** Formats clean printable invoice tickets formatted for thermal receipt printers.
- **Daily Sales Reporting:** Executive daily and monthly revenue summaries for cash balancing.

---

## 🛠️ Technology Stack & Architecture

- **Backend:** PHP 8.2+
- **Database:** MySQL
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5

---

## 🚀 Local Installation & Setup Guide

### 1. Repository Cloning
```bash
git clone https://github.com/pranataa-labs/Simple-Point-Of-Sale.git
cd Simple-Point-Of-Sale
```

### 2. Database Configuration
Import the provided SQL schema dump into your MySQL database (e.g. via phpMyAdmin or MySQL CLI):
```bash
mysql -u root -p pos_database < database.sql
```

### 3. Server Configuration
Configure your database credentials in the database connection configuration file, then host locally via Laragon, XAMPP, or PHP built-in server:
```bash
php -S localhost:8000
```
Open [http://localhost:8000](http://localhost:8000) in your browser.

---

## 📄 License

This repository is open-sourced under the [MIT License](LICENSE).
