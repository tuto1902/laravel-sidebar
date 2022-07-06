# Simple sidebar navigation layout using Laravel Breeze.

## Installation

````
git clone git@github.com:tuto1902/laravel-sidebar.git
````
````
cd laravel-sidebar
````
If you're using Laravel Sail

````
./vendor/bin/sail up -d

sail composer install
````
Otherwise just use

````
sail composer install
````

````
cp .env.example .env
````
If you're using Laravel Sail

````
sail artisan key:generate
````
Otherwise just use

````
php artisan key:generate
````
This step is optional if you're not using Laravel Sail and don't have a database configured.

Using sqlite you can get up to speed quickly

````
touch database/database.sqlite
````
Make sure you uncomment this line in the .env file

```
# DB_CONNECTION=sqlite
```

If you use sqlite, remove or comment out this entire section in the .env file

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_sidebar
DB_USERNAME=root
DB_PASSWORD=
```

If you're using Laravel Sail

````
sail artisan migrate
````
Otherwise just use

````
php artisan migrate
````

````
npm install && npm run prod
````
If you're not using Laravel Sail or Valet, this will spin up a development server.

````
php artisan serve
````