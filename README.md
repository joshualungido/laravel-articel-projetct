# Laravel 11 Website Project

This project is a simple website built with Laravel 11, featuring dynamic pages and database-driven content management. It is an ideal project for showcasing basic Laravel functionality and modern web development practices.

---

## Features

### Pages:
- **Home Page**: A welcoming landing page introducing the website.
- **About Page**: A page describing the purpose of the website.
- **Articles Section**:
  - Users can **view articles** categorized by category and author.
  - **Search functionality**: Users can search for articles by title or author.
  - **Categorization**: Articles are grouped by categories.
- **Contact Page**: A simple form or interface for user communication or feedback.

### Additional Features:
- **Dynamic Data**: Articles, categories, and authors are dynamically managed using Eloquent ORM.
- **Database Integration**:
  - Uses **SQL database** for managing content.
  - Fully integrated migrations and seeders to generate and reset sample data easily.
- **Factories**:
  - Factories generate sample data for testing, such as users, categories, and articles.
- **Relationships**:
  - Each **article** belongs to one **category** and one **author**.
  - Articles can be categorized and filtered.

---

## How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/joshualungido/laravel-articel-projetct.git
2. Navigate to the project directory:
   ```bash
    cd laravel-articel-projetct

4. Install dependencies :
   ```bash
   composer install
    npm install
    npm run dev
6. Set up the environment:
   ```bash
    Create a .env file by copying the .env.example file.
    Configure database settings in the .env file:
    DB_DATABASE=your_database_name
    DB_USERNAME=your_database_username
    DB_PASSWORD=your_database_password

7. Run database migrations and seeders:
   ```bash
   php artisan migrate:fresh --seed
7. Start Application
   ```bash
   npm run dev

