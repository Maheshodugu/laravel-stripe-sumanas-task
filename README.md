# laravel-stripe-sumanas-task
Step 1: Clone/Download the project using Zip download or Git:
git clone git@github.com:Maheshodugu/laravel-stripe-sumanas-task.git

Step 2: Extract the Zip File and open the .env file. Add the database name, for example:
DB_DATABASE=sumanas_task

Step 3: Create the database using MySQL with the same name as specified in the .env file, for example:
CREATE DATABASE sumanas_stripe;

Step 4: Run the following command in the terminal from the project path to execute the database migrations:
php artisan migrate

Step 5: Run the following command in the terminal to seed the database with initial data:
php artisan db:seed --class=ProductSeeder

Step 6: Finally, run the Laravel development server using the following command:
php artisan serve

