# Установка зависимостей и настройка проекта

Этот файл описывает установку зависимостей для проекта на Django, а также настройку документации с использованием MkDocs.

## 1. Установка зависимостей для Django проекта

Для начала установим основные зависимости для вашего Django проекта.

###  [Django](https://docs.djangoproject.com/en/5.1/)
Устанавливаем Django — основную библиотеку для разработки веб-приложений.

```bash
pip install django
```

### [Django Crispy Forms](https://django-crispy-forms.readthedocs.io/en/latest/)
Дает возможность легко стилизовать формы в Django, поддерживает шаблоны Bootstrap.

```bash
pip install django-crispy-forms
```

### [Django Cleanup](https://pypi.org/project/django-cleanup/)
Удаляет неиспользуемые файлы, такие как изображения, когда они удаляются из модели.

```bash
pip install django-cleanup
```

### [Django CKEditor](https://django-ckeditor.readthedocs.io/en/latest/)
Интегрирует CKEditor в Django для редактирования текстов с расширенными возможностями.

```bash
pip install django-ckeditor
```

### [Channels](https://channels.readthedocs.io/en/latest/)
Используется для асинхронных соединений, таких как WebSockets, в Django.

```bash
python3 -m pip install -U channels
```

### [Django Allauth](https://docs.allauth.org/en/latest/)
Позволяет быстро интегрировать аутентификацию пользователей, включая регистрацию, вход через социальные сети и т.д.

```bash
pip install django-allauth
```

### [Python Dotenv](https://pypi.org/project/python-dotenv/)
Управляет конфигурационными переменными, загружаемыми из .env файла.

```bash
pip install python-dotenv
```

### [Django Braces](https://django-braces.readthedocs.io/en/latest/)
Предоставляет набор вспомогательных классов для работы с Django.

```bash
pip install django-braces
```

## 2. Подключение MkDocs для документации

Для создания документации для проекта установим MkDocs.

### [Установк MkDocs](https://www.mkdocs.org/user-guide/installation/)

Устанавливаем сам инструмент MkDocs для генерации документации.

```bash
pip install mkdocs
```

### [Установка MkDocs Material](https://pypi.org/project/mkdocs-material/)
Добавляем тему Material для улучшенного внешнего вида документации.

```bash
pip install mkdocs-material
```

### [Установка Awesome Pages Plugin](https://pypi.org/project/mkdocs-awesome-pages-plugin/)
Этот плагин добавляет удобную навигацию между страницами документации.

```bash
pip install mkdocs-awesome-pages-plugin
```