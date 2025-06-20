# Laravel 12 + Inertia.js + Vue 3 + TailwindCSS 4 Starter Template

[![Latest Version on Packagist](https://img.shields.io/packagist/v/xocdr/laravel-inertia-vue3-starter.svg?style=flat-square)](https://packagist.org/packages/xocdr/laravel-inertia-vue3-starter)
[![Total Downloads](https://img.shields.io/packagist/dt/xocdr/laravel-inertia-vue3-starter.svg?style=flat-square)](https://packagist.org/packages/xocdr/laravel-inertia-vue3-starter)
[![License](https://img.shields.io/packagist/l/xocdr/laravel-inertia-vue3-starter.svg?style=flat-square)](https://packagist.org/packages/xocdr/laravel-inertia-vue3-starter)

A modern starter template for Laravel 12 projects using Inertia.js 2, Vue 3, and TailwindCSS 4. This template provides a solid foundation for building modern web applications with the latest versions of these powerful technologies.

## Features

- 🚀 Laravel 12
- ⚡️ Vite 6 with HMR
- 🎭 Inertia.js 2
- 💚 Vue 3
- 🎨 TailwindCSS 4
- 🐳 Docker with Laravel Sail
- 📝 Laravel Pint for PHP code styling
- 🔍 Laravel Pail for improved logging
- ✅ PHPUnit for testing

## Requirements

- PHP 8.2 or higher
- Composer
- Node.js 20 or higher
- Docker (for Laravel Sail)

## Installation

You can create a new project using Composer:

```bash
composer create-project xocdr/laravel-inertia-vue3-starter your-project-name
cd your-project-name
```

### Development Setup

1. Copy the environment file:
```bash
cp .env.example .env
```

2. Start Laravel Sail:
```bash
./vendor/bin/sail up -d
```

3. Install PHP dependencies:
```bash
./vendor/bin/sail composer install
```

4. Install Node.js dependencies:
```bash
./vendor/bin/sail npm install
```

5. Generate application key:
```bash
./vendor/bin/sail artisan key:generate
```

6. Run database migrations:
```bash
./vendor/bin/sail artisan migrate
```

7. Start the development server:
```bash
./vendor/bin/sail npm run dev
```

Your application will be available at:
- Frontend (Vite): http://localhost:5173
- Backend (Laravel): http://localhost

## Development Commands

- Start all development servers:
```bash
./vendor/bin/sail composer dev
```

- Run tests:
```bash
./vendor/bin/sail composer test
```

- Format PHP code:
```bash
./vendor/bin/sail composer pint
```

## License

This project is open-sourced software licensed under the [MIT license](LICENSE.md).
