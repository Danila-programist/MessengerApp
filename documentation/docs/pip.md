# Установка зависимостей и настройка проекта

Этот файл описывает установку зависимостей для проекта на Django, а также настройку документации с использованием MkDocs.

## 1. Установка зависимостей для Django проекта

Для начала установим основные зависимости для вашего Django проекта.

### Django
Устанавливаем Django — основную библиотеку для разработки веб-приложений.

```bash
pip install django
```

### Django Crispy Forms
Дает возможность легко стилизовать формы в Django, поддерживает шаблоны Bootstrap.

```bash
pip install django-crispy-forms
```

### Django Cleanup
Удаляет неиспользуемые файлы, такие как изображения, когда они удаляются из модели.

```bash
pip install django-cleanup
```

### Django CKEditor
Интегрирует CKEditor в Django для редактирования текстов с расширенными возможностями.

```bash
pip install django-ckeditor
```

### Channels
Используется для асинхронных соединений, таких как WebSockets, в Django.

```bash
python3 -m pip install -U channels
```

### Django Allauth
Позволяет быстро интегрировать аутентификацию пользователей, включая регистрацию, вход через социальные сети и т.д.

```bash
pip install django-allauth
```

### Python Dotenv
Управляет конфигурационными переменными, загружаемыми из .env файла.

```bash
pip install python-dotenv
```

### Django Braces
Предоставляет набор вспомогательных классов для работы с Django.

```bash
pip install django-braces
```

## 2. Подключение MkDocs для документации

Для создания документации для проекта установим MkDocs.

### Установк MkDocs

Устанавливаем сам инструмент MkDocs для генерации документации.

```bash
pip install mkdocs
```

### Установка MkDocs Material
Добавляем тему Material для улучшенного внешнего вида документации.

```bash
pip install mkdocs-material
```

### Установка Awesome Pages Plugin
Этот плагин добавляет удобную навигацию между страницами документации.

```bash
pip install mkdocs-awesome-pages-plugin
```