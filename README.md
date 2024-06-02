# Приложение для заметок на Django

## Описание

Это приложение для управления заметками. Вы можете добавлять, редактировать, просматривать и удалять заметки.
Приложение разработано с использованием фреймворка Django и Bootstrap.

## Требования

- Python 3.x
- Django 3.x или выше

## Установка

1. **Клонируйте репозиторий:**

   ```bash
   git clone https://github.com/ваш-репозиторий.git
   cd ваш-репозиторий
   ```
2. **Создайте виртуальное окружение:**

    ```bash
    python -m venv venv
    ```
3. **Активируйте виртуальное окружение:**

   На Windows:

    ```bash
    venv\Scripts\activate
    ```
   На macOS и Linux:

    ```bash
    source venv/bin/activate
    ```

4. **Установите зависимости:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Создайте и примените миграции базы данных:**

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

6. **Запустите сервер разработки:**

   ```bash
   cd notesapp      
   python manage.py runserver
   ```

7. **Откройте браузер и перейдите по адресу:**

   [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
   
