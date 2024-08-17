## Install laravel
```
laravel new lara11-pretty-auth
```

## Install DevDojo/Auth
https://devdojo.com/auth/docs/install/breeze/

```
composer require devdojo/auth
```

Next, you'll need to publish the assets, configs, ci workflow, and migrations:

```
php artisan vendor:publish --tag=auth:assets
php artisan vendor:publish --tag=auth:config
php artisan vendor:publish --tag=auth:ci
php artisan vendor:publish --tag=auth:migrations
```

Next, you'll want to run the new migrations:

```
php artisan migrate
```
