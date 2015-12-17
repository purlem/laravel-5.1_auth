## Laravel 5.1 with Authentication

Create .env file

    vi .env

    APP_NAME=App
    
    APP_ENV=local
    APP_DEBUG=true
    
    DB_CONNECTION=sqlite
    
    CACHE_DRIVER=file
    SESSION_DRIVER=file
    QUEUE_DRIVER=sync

Install composer

    composer install
  
Generate App Key

    php artisan key:generate

Create Database

    vi storage/database.sqlite
  
Migrate Database

    php artisan migrate

  

---

See here for notes/install: http://martythomas.svbtle.com/adding-authentication-to-laravel-51
