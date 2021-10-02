# Verify Email and Reset Password Laravel
### laravel 8

install
```
composer update
composer require laravel/ui
php artisan ui vue --auth
npm install
npm run dev
```

Setup *.env* config 
```
MAIL_MAILER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=yourgmail@gmail.com
MAIL_PASSWORD=passwordgmail
MAIL_ENCRYPTION=tls
MAIL_FROM_ADDRESS=yourgmail@gmail.com
MAIL_FROM_NAME=username//"${APP_NAME}"

```

Run
1. php artisan key:generate
2. php artisan migrate
3. php artisan serve

