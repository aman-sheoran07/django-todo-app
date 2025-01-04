# Django Todo App

A feature-rich Todo application built with Django and PostgreSQL.

## Features

- User Authentication (Register/Login/Logout)
- Create, Read, Update, Delete Todos
- Set Priority Levels
- Due Date Tracking
- Mark Tasks as Complete/Incomplete
- PostgreSQL Database Integration

## Installation

1. Clone the repository:
```bash
git clone https://github.com/aman-sheoran07/django-todo-app.git
cd django-todo-app

python -m venv venv
source venv/bin/activate  # Linux/Mac
# or
venv\Scripts\activate  # Windows

pip install -r requirements.txt

python manage.py migrate

python manage.py createsuperuser

python manage.py runserver