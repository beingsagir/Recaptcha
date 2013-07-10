Recaptcha
=========

Laravel 4 Recaptcha Package

## Installation
1.  Run  `composer require sb89/recaptcha`
2.  Add `'Sb89\Recaptcha\RecaptchaServiceProvider'` to the providers array in `app/config/app.php`
3.  Run `php artisan config:publish sb89/recaptcha`
4.  Add you Recaptcha Private and Public keys to the `app/config/packages/sb89/recaptcha/config.php`

## Usage
1.  `Form:recaptcha()`
2.  Add `recaptcha_response_field' => 'required|recaptcha` to your validation rules

