# Демо-проект интернет магазина

## Данный демо-проект реализован на python фреймворке Django 2.2
<hr>

#### В проекте реализовано:
* админ панель с возможностью редактирования содержания магазина
* регистрация и аутентификация пользователей
* добавление товаров в корзину и оформление заказа
* возможность оставлять комментарии к товарам
<hr><br><br>
Главная страница:

![Иллюстрация к проекту](https://github.com/tihon49/Shop_DEMO/blob/master/media/main_page.png)

<br><br>

Страница товара:

![Иллюстрация к проекту](https://github.com/tihon49/Shop_DEMO/blob/master/media/item.png)

<br><br>

Страница корзины:

![Иллюстрация к проекту](https://github.com/tihon49/Shop_DEMO/blob/master/media/cart.png)

<hr><br>

## Для запуска проекта необходимо:

установить необходимые библиотеки:
```commandline
pip install -r requirements.txt
```

произведем миграции
```commandline
python manage.py migrate
```

загрузить базовое наполнение магазина:
```commandline
python manage.py loaddata shop.json
```

Теперь нам доступна демо-версия интернет маназина, а так же админ пользователь:
```commandline
login: admin
password: admin
```

Команда для запуска сервера:
```commandline
python manage.py runserver
```

*Переходим на [сайт магазина](http://127.0.0.1:8000/)*

