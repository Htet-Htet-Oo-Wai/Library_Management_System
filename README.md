## Name
Library Management System

## Setup Guide for Laravel
```
git clone https://github.com/Htet-Htet-Oo-Wai/Library_Management_System.git
cd into cloned project folder
cd src
run composer install
copy of .env.example and rename it to .env
change DB section with your local MySQL database setting
create new database in your local MySQL
run php artisan migrate:fresh --seed
run php artisan key:generate
run php artisan serve
can be accessed at http://localhost:8000/
run php artisan schedule:work to test schedule
```

## Login credentials for admin dashboard
```
email => admin@gmail.com
password => password
```

## Versions I have used
- PHP => ^8.1
- Laravel framework => ^10.10
- MySQL => 8.0

## Setup to send mail
```
replace mail section in env with your sender mail
MAIL_MAILER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=yourmail@gmail.com
MAIL_PASSWORD=your app password generated from mail
MAIL_ENCRYPTION=tls
MAIL_FROM_ADDRESS=yourmail@gmail.com
MAIL_FROM_NAME="${APP_NAME}"
```
