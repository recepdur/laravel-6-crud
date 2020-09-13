 
composer install
composer create-project --prefer-dist laravel/laravel blog
php artisan key:generate
create database in phpmyadmin with name: DB_DATABASE=blog in .env file
create migration command: php artisan make:migration create_students_table --create=students
run migration command: php artisan migrate
create controller command: php artisan make:controller StudentController --resource --model=Student
run server command: php artisan serve
