
# POS Application (Point of Sales) using Laravel

## About the Application

The POS or Point of Sales application manages transactions in stores or by cashiers. Developed on Laravel v8.* and requiring PHP v7.4 minimum, potential errors or bugs during installation may stem from unsupported PHP versions.

## Key Features

- Product Category Management
- Product Management
  - Multiple Deletion
  - Barcode Printing
- Member or Customer Management
  - Member Card Printing
- Supplier Management
- Expense Transactions
- Purchase Transactions
- Sales Transactions
- Income or Profit & Loss Reports
  - Monthly, Daily, Custom Dates
- Custom Invoice Types
  - Large Invoice
  - Small / Thermal Invoice
- User and Profile Management
- Store Settings
  - Identity
  - Member Card Design Upload
  - Member Discount Settings
- User Roles (Administrator, Cashier)
- ChartJS Graphs on Dashboard

## Application Setup


1. Run the command:
   ```bash
   composer update

## Setup Aplikasi
run in terminal
```bash
composer update
```
or:
```bash
composer install
```
Copy file .env dari .env.example
```bash
cp .env.example .env
```
Konfigurasi file .env
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=example_app
DB_USERNAME=root
DB_PASSWORD=
```
Opsional
```bash
APP_NAME=Laravel
APP_ENV=local
APP_KEY=base64:QGRW4K7UVzS2M5HE2ZCLlUuiCtOIzRSfb38iWApkphE=
APP_DEBUG=true
APP_URL=http://example-app.test
```
Generate key
```bash
php artisan key:generate
```
Migrate database
```bash
php artisan migrate
```
Seeder table User, Pengaturan
```bash
php artisan db:seed
```
Run Application
```bash
php artisan serve
```

## License

[MIT license](https://opensource.org/licenses/MIT)
