#Обрезка ссылок с помощью Битли
***
Программа позволяет сокращать ссылки, используя сервис Битли, а также получать количество кликов по полученным сокращенным
ссылкам.

## Как установить

Python3 должен быть уже установлен. Затем используйте pip (или pip3, есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```
Для работы необходимо создать учетную запись на сайте [bitly.com](https://bitly.com) и сгенерировать access token
в личном кабинете сервиса. Далее создать в папке проекта файл .env и положить в него токен по образцу: BITLINK_TOKEN=['Ваш токен']).

## Как использовать
Запускаем программу с ссылкой, которую вы хотите сократить, например:
```
python main.py https://sports.ru
```

## Цель проекта
Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org).