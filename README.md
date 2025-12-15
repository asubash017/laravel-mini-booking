# Laravel Mini Booking

A simple Laravel-based booking system project, ideal for learning Laravel, database interactions, and basic web app structure.

## Table of Contents

- [Features](#features)  
- [Installation](#installation)  
- [Configuration](#configuration)  
- [Usage](#usage)  
- [Technologies](#technologies)  
- [Contributing](#contributing)  
- [License](#license)  

## Features

- User authentication (login/register)  
- Basic booking management  
- Session handling  
- Database-driven caching and queue support  
- Responsive UI with Vite  

## Installation

1. Clone the repository:

```bash
git clone https://github.com/asubash017/laravel-mini-booking.git
cd laravel-mini-booking

composer install

npm install

cp .env.example .env

php artisan key:generate

php artisan migrate

php artisan serve

npm run dev
