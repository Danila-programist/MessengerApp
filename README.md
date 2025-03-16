Новый проект для создания мессенджера с использованием фреймворка Django


1. Создание папки для виртуального окружения practice_djangoEnv
2. Создание игнорирования папки пункта 1
3. Установка django 
`pip install django`
`pip install django-crispy-forms`
`pip install django-cleanup`
`pip install django-ckeditor`
`python3 -m pip install -U channels`
`pip install django-allauth`
`pip install python-dotenv`
`pip install django-braces`
4. Запуск шаблона проекта
`django-admin startproject messengerApp`
5. Подключение mkdocs
`pip install mkdocs`
6. Создание структуры докуменатации
`pip install mkdocs-material`
`pip install mkdocs-awesome-pages-plugin`
запуск через 127.0.0.1:8200
7. Создание файла  bash для установки всех зависимостей
8. Заполнение pip.md 
9. Заполнение миграций
`python manage.py collectstatic`
и изменение gitignore 
10. Создание суперпользователя
`python manage.py createsuperuser`
и миграции
`python manage.py makemigrations`
`python manage.py migrate`
11. Запуск админки  127.0.0.1:8000/admin/
12. Cоздание суперпользователя
`python manage.py createsuperuser`
13. Добавление installed_apps в settings нового параметра 'blog' 
`python manage.py startapp blog`