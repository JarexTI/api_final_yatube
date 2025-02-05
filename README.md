# API социальной сети Yatube (RU)

Описание проекта
---
Проект представляет собой создания API для платформы Yatube. API обрабатывает создание, редактирование и удаление постов, групп и комментариев с аутентификацией через JWT токены. Он предназначен для использования аутентифицированными пользователями для изменения своего контента, в то время как другие действия доступны только для чтения. Проект включает эндпоинты для управления подписками (модель Follow) с методами GET и POST, а также обеспечивает правильную обработку ошибок и безопасность.

Основные задачи
---
✔️ Реализация модели Follow с эндпоинтами для управления подписками  
✔️ Аутентификация через JWT токены для доступа пользователей  
✔️ Доступ только для чтения для не аутентифицированных пользователей с ограниченными правами на изменение

Стек технологий
---
- Python 3.9
- Django REST Framework 3.12
- Django 3.2
- SQLite3

Установка проекта из репозитория (Windows)
---
1. Клонировать репозиторий:
```bash
git clone git@github.com:JarexTI/api_final_yatube.git
```
2. Перейти в папку проекта:
```bash
cd api_final_yatube
```
3. Создать и активировать виртуальное окружение:
```bash
python -m venv venv

source venv/Scripts/activate
```
4. Установить зависимости из файла `requirements.txt`:
```bash
python -m pip install --upgrade pip

pip install -r requirements.txt
```
5. Выполнить миграции:
```bash
python yatube_api/manage.py migrate
```
6. Запустить проект:
```bash
python yatube_api/manage.py runserver
```

Документация к API
---
После запуска сервера, по адресу [http://127.0.0.1:8000/redoc/](http://127.0.0.1:8000/redoc/) доступна документация к API.
<br>
<br>

# Yatube Social Network API (EN)

Project Description
---
This project involves the creation of an API for the Yatube platform. The API handles the creation, editing, and deletion of posts, groups, and comments, with authentication via JWT tokens. It is designed for use by authenticated users to modify their content, while other actions are available only for reading. The project includes endpoints for managing subscriptions (Follow model) with GET and POST methods and ensures proper error handling and security.

Key Features
---
✔️ Implementation of the Follow model with endpoints for managing subscriptions  
✔️ Authentication via JWT tokens for user access  
✔️ Read-only access for unauthenticated users with limited modification rights

Technology Stack
---
- Python 3.9
- Django REST Framework 3.12
- Django 3.2
- SQLite3

Project Installation from Repository (Windows)
---
1. Clone the repository:

```bash
git clone git@github.com:JarexTI/api_final_yatube.git
```

2. Navigate to the project folder:

```bash
cd api_final_yatube
```

3. Create and activate a virtual environment:

```bash
python -m venv venv

source venv/Scripts/activate
```

4. Install dependencies from the `requirements.txt` file:

```bash
python -m pip install --upgrade pip

pip install -r requirements.txt
```

5. Apply migrations:

```bash
python yatube_api/manage.py migrate
```

6. Run the project:

```bash
python yatube_api/manage.py runserver
```

API Documentation
---
After starting the server, the API documentation can be accessed at [http://127.0.0.1:8000/redoc/](http://127.0.0.1:8000/redoc/).
