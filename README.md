# Laravel SMTP Configuration


[![Latest Version on Packagist](https://img.shields.io/packagist/v/nilesh/laravel-smtp.svg?style=flat-square)](https://packagist.org/packages/nilesh/laravel-smtp)
[![Latest Issue](https://img.shields.io/github/issues/nileshmailbook/smtp.svg?style=flat-square)](https://github.com/nileshmailbook/laravel-smtp/issues)
[![Total Downloads](https://img.shields.io/packagist/dt/nilesh/laravel-smtp.svg?style=flat-square)](https://packagist.org/packages/nilesh/laravel-smtp)

 
## Description

# This package allow user to create own smtp in existing project and allow sending mail through it.

#simply call /smtp route and fill the details of your smtp and and tested on their.

#this package extend the laravel mail on the fly, no need to configure .env or config/mail.php

#hassle free package available form laravel 5.8.*  


### Laravel

This package can be used in Laravel 5.8 or higher.

You can install the package via composer:

``` bash
composer require nilesh/laravel-smtp
```

The service provider will automatically get registered.

After the installing this package run the migrations:

```bash
php artisan migrate
```



After successfull running migrate just start your local server and login in your app type url localhost:8000/smtp url in adress bar.
now configure the smtp and try to check your smtp is workable in test mail section.

If you want to change UI of smtp Configuration you may wish to publish in view

simply publish the view

```bash
php artisan vendor:publish
```

Now enjoy the simple mail function on the fly.
Alternate link if this package not working : https://github.com/nileshmailbook/smtp

