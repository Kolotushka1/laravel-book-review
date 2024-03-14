## Проект Laravel-book-review сайт для оценки книг
CRUD проект, который имеет тематику рецензии книг
## **Для развертывания поднадобится установить Docker**
После выполнить команду
```
docker compose up
```
Env.example -> переименовать в env и настроить БД (создать в Adminer)
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel-10-task-list
DB_USERNAME=root
DB_PASSWORD=root
```
Затем заполнить базу данным данными
```
php artisan migrate
php artisan db:seed
```
Можно воспользоватья проектом!
