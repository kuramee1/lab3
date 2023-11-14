# lab3
# Інструкція по розгортанню
Крок 1: Встановлення залежностей
Вам слід мати встановлений Python 3.7 та pipenv

pipenv install

Крок 2: Активація віртуального середовища

pipenv shell
 
Крок 3: Локальне встановлення Waitress

cd C:\Users\Max\PycharmProjects\pythonProject
pipenv install waitress
pipenv install werkzeug --dev

Крок 4: Запуск серверу

pipenv run waitress-serve --host=127.0.0.1 main:app

Крок 5: Тестування роботи серверу

перейти в браузері за посиланням: http://127.0.0.1:8080/api/v1/hello-world-20/