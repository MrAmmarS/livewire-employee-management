# laravel-livewire-employees-management

## About this project 

This is my testing projects to produce employee management systems with laravel livewire

Features

- Login System
- User Management
- Roles Management
- Basic CRUD

## Clone guide line

Install the dependencies and start server

```sh
git clone https://github.com/MrAmmarS/livewire-employee-management.git 
cd projects/employee-management
composer install && composer du
```

if .env file is not exsists yet, consider copy from .env.example
```sh
cp .env.example file if .env is not exists
```

set up your database file first, then proceed this line of code
```sh
php artisan optimize
php artisan key:generate
php artisan migrate:fresh
```

then proceed to start server
```sh
npm run dev // npm run watch
php artisan serve
```

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

