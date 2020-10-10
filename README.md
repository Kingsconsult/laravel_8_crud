# laravel_8_crud
This is a simple laravel 8 CRUD app.
The repository is the code to one of my article on **Dev.to**, [Laravel 8 CRUD App, A simple guide](https://dev.to/kingsconsult/laravel-8-crud-bi9) the article will teach you how to create a CRUD app on Laravel 8, the method is applicable to Laravel 6 and also Laravel 7 

## How to install and run on your local system
1. git clone https://github.com/Kingsconsult/laravel_8_crud.git
2. cd laravel_8_crud/
3. composer install
4. npm install
5. cp .env.example .env
6. php artisan key:generate
7. Add your database config in the .env file (you can check my articles on how to achieve that)
8. php artisan migrate
9. php artisan serve (if the server opens up, http://127.0.0.1:8000,  then we are good to go)
![localhost](https://res.cloudinary.com/kingsconsult/image/upload/v1600705305/laravel%208%20modal/4_pp7r76.png)
10. Navigate to http://127.0.0.1:8000/projects
![CRUD](https://res.cloudinary.com/kingsconsult/image/upload/v1602364575/crud_llekuf.png)

## Operations
1. Create a project
2. View a project
3. Edit a project
4. Delete a project
5. View all projects
