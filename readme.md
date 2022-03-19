1. Run `git clone https://github.com/amadoalcantara/git-sevs.git`
2. Run `cd Voting-System`
3. Run `cp .env.example .env` or rename .env.example to .env
4. Open .env file and Setup your database connection
5. Run `composer install`
6. Run `php artisan migrate --seed`
7. Run `php artisan storage:link`
8. Run `php artisan key:generate`
9. Run `php artisan passport:install`
10. Finally run `php artisan serve`