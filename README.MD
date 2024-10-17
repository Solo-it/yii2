# Тестовый проект по PHP с Docker

****

## Информация взята со статьи

https://thriveread.com/apache-php-with-docker-mysql-and-phpmyadmin/


## Как зайти внутрь докер контейнера

    docker-compose exec webserver bash


# Генерация SSH ключа

    ssh-keygen

Так же нужно создать файл конфига по пути:

    ~/.ssh/config


## Удаленное подключение по ssh без пароля

    ssh-copy-id -i ~/.ssh/mykey stv

Вводим пароль, и после этого у нас будет работать: 

    ssh stv
