Установка :

Выполнить команду : 

composer install (update);
npm install (при необходимости);
php artisan key:generate
php artisan storage:link(при необходимости);
php artisan optimize:clear(при необходимости);
Переименовать файл .env.example в файл .env и настроить подключение к базе данных и пр;
Использованы :
-Laravel;

Дамп базы данный Social_Network.sql;

Стартовая страница:
public\index.php


Тестовое задание

Стек технологий: Laravel 7, PHP 7.4

Задача: Функционал друзей. Создать REST API
Пользователь может зарегистрироваться в приложении и 
отправить запрос «пригласить в друзья» любому другому пользователю.
Другой пользователь может принять или отклонить это приглашение.
В проекте должен быть документ API для всех конечных точек. 
Должен быть README с описанием того, как запустить проект локально.
Полученный код нужно отправить в публичный репозиторий 
github и поделиться ссылкой.

Дополнительная задача: 
добавить файлы docker / docker-compose 
для запуска этого проекта
