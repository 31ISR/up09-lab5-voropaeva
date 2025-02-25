# Django проект

## Функции
* Главная старница
* Страница "Обо мне"
* Страница постов
* Страница сообществ
* Регистрация и авторизация
* Админ-панель
* Создание сообществ и постов

## Установка и запуск

**1.Клонировать репазиторий:**
```bush
git clone https://github.com/31ISR/up09-lab5-voropaeva.git
cd up09-lab5-voropaeva/lab1/lab1
```

**2.Создать и активировать виртуальное окружение:**
```bush
python -m venv venv
source venv/bin/activate
```

**3.Установить зависимости:**
```bush
pip install -r requirements.txt
```

**4.Применить миграции:**
```bush
python manage.py migrate
```

**5.Запустить сервер:**
```bush
python manage.py runserver
```

## Страницы
* `/` - Главная страница
* `/about/` - Обо мне
* `/posts/` - Посты
* `/communities/` - Сообщества
* `/register/` - Регистрация
* `/login/` - Войти
* `/new-post/` - Создать пост
* `/new-communities/` - Создать сообщество

## Админ-панель
Админ-панель доступна по адресу `/admin/`. Для доступа необходимо:

1.Создать суперпользователя:
```bush
python manage.py createsuperuser
```
2.Войти с логином/паролем суперпользователя

***

**Автор:** zhenyal123