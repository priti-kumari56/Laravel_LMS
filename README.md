# 🎓 E-Learning Platform (Laravel)

> A learning management system built using Laravel.  
> Originally created in **Laravel 5.4 (2016)** and later upgraded to **Laravel 10** for testing and modernization.

---

## 📌 About This Project

This project was initially developed in **Laravel 5.4** during the learning phase.  
Recently, it has been upgraded to **Laravel 10** as an experiment to track upgrade steps and compatibility.

> ⚠️ Note: This is a legacy project without formal test cases. Some bugs or inconsistencies may still exist.

---

## 🛠 Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/emtiazzahid/e-learning.git
cd e-learning
```

### 2. Install Dependencies

```bash
composer install
```

### 3. Set Up the Environment File

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Run Migrations and Seeders

```bash
php artisan migrate --seed
```

### 5. Serve the Application

```bash
php artisan serve
```

Then open your browser at:  
🌐 [http://localhost:8000](http://localhost:8000)

---

## 🔐 Admin Login Credentials

```text
Email:    admin@mail.com  
Password: password
```

---

## 📜 License

This project is open-source and available for use, modification, and learning purposes.

---
