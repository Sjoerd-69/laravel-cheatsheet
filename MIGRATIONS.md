# Laravel Notes: Migrations

### Navigation
- [Home](https://github.com/Sjoerd-69/laravel-cheatsheet/blob/main/README.md)
- [Installation / Basics](https://github.com/Sjoerd-69/laravel-cheatsheet/blob/main/INSTALLATION.md)
- [Controller](https://github.com/Sjoerd-69/laravel-cheatsheet/blob/main/CONTROLLER.md)
- [Model](https://github.com/Sjoerd-69/laravel-cheatsheet/blob/main/MODEL.md)
- Migrations
- [Routing](https://github.com/Sjoerd-69/laravel-cheatsheet/blob/main/ROUTING.md)

### Relations in an migration
```php
$table->unsignedBigInteger('example_id');
$table->foreign('example_id')->references('id')->on('example');
```

### Normal migration
```
php artisan migrate   
```
### Fresh migration
```
php artisan migrate:fresh
```
