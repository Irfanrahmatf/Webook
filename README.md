<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>


## INSTALLATION 
<p>This project using laravel version 10 and php 8</p>

### 1. Install PHP, Composer, and Yarn
- Download PHP https://www.php.net/downloads.php recommended version 8.0.0 or newer
- Download composer https://getcomposer.org/
- Download yarn https://classic.yarnpkg.com/en/
- Check if success install PHP and composer
```sh
php --version
```
```sh
composer --version
```
```sh
yarn --version
```
### 2. Clone Repository Project App
- Clone with `ssh`
    ```sh
    git@github.com:Irfanrahmatf/Webook.git
    ```
- Clone with `https`
    ```sh
    https://github.com/Irfanrahmatf/Webook.git
    ```

switch to the repo folder
```sh
cd Webook
```
### 3. Install Dependency
```sh
composer install
```
```sh
yarn
```
### 4. Configure .env
In the .env.example file rename it to .env then run the command: 
```sh
php artisan key:generate
```
### 5. Create Symbolic Link for Storage
Create symbolic links between public/storage directories and storage/app/public. This is required for files stored on storage/app/public to be accessed directly through the web.
Run the following command:
```sh
php artisan storage:link
```
### 7. Create Database and Migrations
- Create database (sql) nama : laravel
- Then migrate the model table :
```sh
php artisan migrate --seed
```

### 8. Running App
defaut host port running dev http://localhost:8000
```sh
php artisan serve
```

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

