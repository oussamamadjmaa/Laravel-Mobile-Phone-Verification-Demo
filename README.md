# Laravel Mobile Phone Verification Demo

This is a Laravel 9 demo project with verifying the phone number via SMS, after the registration.

The goal was to mimic a similar process as in the official [Email Verification](https://laravel.com/docs/9.x/verification) feature of Laravel.

Registration process is based on Laravel Breeze.

SMS Sending is performed with Notifications, based on Vonage (ex Nexmo) provider, which is [officially supported by Laravel](https://laravel.com/docs/9.x/notifications#sms-notifications).

## Server Requirements
The Laravel framework has a few system requirements. You should ensure that your web server has the following minimum PHP version and extensions:

- PHP >= 8.0
- sodium PHP Extension *(it must be enabled via `php.ini` before running `composer install`)*
- BCMath PHP Extension
- Ctype PHP Extension
- cURL PHP Extension
- DOM PHP Extension
- Fileinfo PHP Extension
- JSON PHP Extension
- Mbstring PHP Extension
- OpenSSL PHP Extension
- PCRE PHP Extension
- PDO PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension
- 
## Usage

- Clone the repository with `git clone`
- Copy `.env.example` file to `.env` and edit database credentials there
- Run `composer install`
- Run `php artisan key:generate`
- Run `php artisan migrate`
- That's it: launch the main URL and click `Register` on the top-right

---

## More from Laravel Daily

- Enroll in our [Laravel Online Courses](https://laraveldaily.teachable.com/?utm_source=github&utm_campaign=mobile-phone-verification)
- Check out our adminpanel generator [QuickAdminPanel](https://quickadminpanel.com/?utm_source=github&utm_campaign=mobile-phone-verification)
- Subscribe to our [YouTube channel Laravel Daily](https://www.youtube.com/c/LaravelDaily)
- Subscribe to our [newsletter with 20+ Laravel links every Thursday](http://laraveldaily.com/weekly-laravel-newsletter/)
