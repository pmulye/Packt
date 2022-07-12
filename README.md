# laravel_8

## How to install and run on your local system
1. git clone https://github.com/pmulye/Packt.git
2. cd laravel_8_packt/
3. composer install
4. npm install
5. cp .env.example .env
6. php artisan key:generate
7. Add your database config in the .env file (you can check my articles on how to achieve that)
8. php artisan migrate
9. php artisan serve (if the server opens up, http://127.0.0.1:8000,  then we are good to go)
10. Navigate to http://127.0.0.1:8000/projects/apiwithkey

