# Book Manager

A **Book Manager** built with Laravel, for managing book information.

## Requirements

Before starting, make sure you have installed:

- [PHP](https://www.php.net/downloads) (version 7.3 or higher)
- [Composer](https://getcomposer.org/download/)

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/lucianookdp/book-manager-laravel.git
cd book-manager-laravel
```

### 2. Install dependencies

```bash
composer install
```

### 3. Configure the environment

1. Rename `.env.example` to `.env`.
2. Open `.env` and set your database credentials.

### 4. Generate the app key

```bash
php artisan key:generate
```

### 5. Run migrations

```bash
php artisan migrate
```

### 6. Start the local server

```bash
php artisan serve
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

## License

All rights reserved. Copying or redistributing without authorization is not
permitted.
