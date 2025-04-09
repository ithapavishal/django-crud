# Django CRUD App
A simple task management app built with Django and PostgreSQL.

## Setup
1. Clone the repo: `git clone https://github.com/ithapavishal/django-crud.git`
2. Create virtual environment: `virtualenv crudenv`
3. Activate: `source crudenv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Set up PostgreSQL and update `settings.py` with your DB credentials.
6. Run migrations: `python manage.py migrate`
7. Start server: `python manage.py runserver`

## Features
- Create, read, update, and delete tasks
- Bootstrap-styled UI