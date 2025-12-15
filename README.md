# Mini Booking Laravel Project

A simple Laravel-based booking application for learning and experimentation purposes.

---

## Features
- Laravel 10 backend
- MySQL database
- Basic session and cache handling
- Uses Vite for frontend asset bundling
- Configured with environment variables for security

---

## Requirements
- PHP >= 8.1
- Composer
- Node.js >= 20 (for Vite)
- MySQL

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/mini-booking.git
cd mini-booking

2. Copy .env.example to .env:

cp .env.example .env


3. Edit .env and set your database credentials:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=mini_booking
DB_USERNAME=your_db_user
DB_PASSWORD=your_db_password


4. Install PHP dependencies:

composer install


5. Install Node dependencies:

npm install
npm run dev


6. Generate app key:

php artisan key:generate


7. Run migrations:

php artisan migrate

8. Running the Project
php artisan serve


Visit http://localhost:8000
 in your browser.
