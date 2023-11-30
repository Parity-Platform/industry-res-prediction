Parity Platform - Industry 4.0
==============================

## About

!['Parity Platform Industry 4 - Dashboard'](./images/parity-industry4-dashboard-screenshot.png)

## Requirements

- PHP 7.3
- MySQL
- NodeJS

## Install & Run webapp

```
composer install
npm install
```
Create a new database in MySQL and copy the name in the `.env` file. Make sure the `.env` file is created, if not copy the `.env.example` and name it `.env`, then run
```
php artisan migrate
```

## Open source technologies

- Laravel framework
- VueJS
- VuetifyJS
- ChartJS