# API для учебного проекта YaTube
Проект позволяет связывать приложения с сервисом YaTube для обеспечения пользователям кроссплатформенного доступа с использованием REST API.

## Использованные технологии:
- Python 3.10
- Django 3.2.16
- DRF
- JWT + Djoser

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

* Если у вас Linux/macOS

    ```
    source venv/bin/activate
    ```

* Если у вас windows

    ```
    source venv/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

## Примеры запросов к API:

После запуска сервера документация доступна по адресу: http://localhost:8000/redoc/

## Автор:

Игорь Андреев