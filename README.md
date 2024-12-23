<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/yourusername/book-review/actions"><img src="https://github.com/yourusername/book-review/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/yourusername/book-review"><img src="https://img.shields.io/packagist/dt/yourusername/book-review" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/yourusername/book-review"><img src="https://img.shields.io/packagist/v/yourusername/book-review" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/yourusername/book-review"><img src="https://img.shields.io/packagist/l/yourusername/book-review" alt="License"></a>
</p>

## About Book Review

Book Review is a web application built with Laravel that allows users to review and rate books. The application provides features such as:

- Simple, fast routing engine.
- Powerful dependency injection container.
- Multiple back-ends for session and cache storage.
- Expressive, intuitive database ORM.
- Database agnostic schema migrations.
- Robust background job processing.
- Real-time event broadcasting.

Book Review is accessible, powerful, and provides tools required for large, robust applications.

## Features

- Search for books by title.
- Filter books by popularity and rating.
- View detailed book information and reviews.
- Add, edit, and delete book reviews.
- User authentication and authorization.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/ZaharPa/book-review.git
    cd book-review
    ```

2. Install dependencies:
    ```sh
    composer install
    npm install
    ```

3. Copy the  file to  and configure your environment variables:
    ```sh
    cp .env.example .env
    ```

4. Generate an application key:
    ```sh
    php artisan key:generate
    ```

5. Run the database migrations:
    ```sh
    php artisan migrate
    ```

6. Seed the database with sample data:
    ```sh
    php artisan db:seed
    ```

7. Build the front-end assets:
    ```sh
    npm run dev
    ```

8. Start the development server:
    ```sh
    php artisan serve
    ```

## Security Vulnerabilities

If you discover a security vulnerability within Book Review, please send an e-mail to [your-email@example.com](mailto:your-email@example.com). All security vulnerabilities will be promptly addressed.

## License

The Book Review project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
