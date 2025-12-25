# Employee Management System (Laravel)

A web-based Employee Management System built using **Laravel 10**, **PHP 8.2**, **SQLite**, and **Vite**.  
This project provides authentication, role-based access, and a structured dashboard for managing employees and organizational data.

---

## 👤 Author

**Rishu Bhardwaj**  
B.E. Computer Science Engineering 

---

## 🚀 Features

- User Authentication (Register / Login)
- Role-based access control
- Dashboard interface
- Employee management structure
- Department & designation support
- SQLite database (easy local setup)
- Vite-powered frontend assets

---

## 🛠️ Tech Stack

- **Backend:** Laravel 10 (PHP 8.2)
- **Frontend:** Blade + Vite
- **Database:** SQLite
- **Authentication:** Laravel Auth
- **Version Control:** Git

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone <your-repo-url>
cd employee-management-system-main
### 2️⃣ Install backend dependencies
composer install
### 3️⃣ Install frontend dependencies
npm install
### 4️⃣ Environment configuration
cp .env.example .env
php artisan key:generate
### 5️⃣ Run database migrations & seeders
php artisan migrate --seed
### 6️⃣ Build frontend assets
npm run build
### 7️⃣ Start the development server
php artisan serve
### Open your browser and visit:http://127.0.0.1:8000

