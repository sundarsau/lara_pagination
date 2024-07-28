# Use Laravel pagination in Laravel 11
 Laravel 11 Project with pagination. This application creates some dummy data using Laravel Seeder and then uses Laarvel pagination paginate() method to display them in pages. Go through the tutorial https://codehow2.com/laravel/how-to-use-laravel-pagination

# How To Use
1. Download the repository from https://github.com/sundarsau/lara_datatables

2. Extract it into a folder

3. Create a Database in MySQL

4. Copy .env.example to .env. Update .env file, change DB_CONNECTION to mysql. Uncomment the lines with DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME and DB_PASSWORD. Update DB_DATABASE with the database name you just created.

5. Run composer install from project root

6. Run php artisan key:generate

7. Run php artisan migrate to create Laravel default tables
   
8. Run php artisan db:seed to create dummy data in users table

9. Run php artisan serve

10. In Browser run localhost:8000


# License
This is an MIT license, you can modify the code according to your requirements
