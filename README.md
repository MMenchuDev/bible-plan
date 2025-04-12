# Bible plan
A web application built with Laravel and Filamentphp.

## About
Helps users track and respond to daily readings from a yearly Bible plan.

## Requirements
- PHP >= 8.1
- Composer
- Node.js & NPM
- MySQL

## Installation
1. Clone the repository
   ```bash
   git clone https://github.com/MMenchuDev/bible-plan.git
   cd bible-plan

2. Install dependencies 
   ```bash
   composer install 
   npm install
   
3. Set up environment
   ```bash
   cp .env.example .env
   php artisan key:generate
   
4. Configure database in .env file
    ```bash
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=bible_plan
   DB_USERNAME=your_username
   DB_PASSWORD=your_password
   
5. Run migrations
    ```bash
   php artisan migrate
   
4. Run the app in local
    ```bash
   composer run dev

## Requirements
- Reading plan customization
- Daily reading tracker
- Progress statistics

## Requirements
[MIT](LICENSE) `
