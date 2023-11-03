# laravel-stripe-sumanas-task
Step 1: Clone/Download the project using Zip download or Git:
git clone git@github.com:Maheshodugu/laravel-stripe-sumanas-task.git

Step 2: Extract the Zip File and open the .env file. Add the database name and the Stripe keys:

DB_DATABASE=sumanas_task
STRIPE_KEY=pk_test_51O7JsDSJFZRWJc072ZBlyhVjNJJM2kjPw5CwYAkKFHYDJrCYbmNrrhCvnGzPT04EDRt2oZ6WT3sKvElNMYAXFN9300MLJ1qLkH
STRIPE_SECRET=sk_test_51O7JsDSJFZRWJc07fbwPd77vhV6UR8a8ECttJeSIuSSbfULBk3z1O8eG1biXCTo50HxuelWkM0x0D0RAZl0Z6kaM00cGY6eSsW

Step 3: Create the database using MySQL with the same name as specified in the .env file, for example:
CREATE DATABASE sumanas_stripe;

Step 4: Run the following command in the terminal from the project path to execute the database migrations:
php artisan migrate

Step 5: Run the following command in the terminal to seed the database with initial data:
php artisan db:seed --class=ProductSeeder

Step 6: Finally, run the Laravel development server using the following command:
php artisan serve

