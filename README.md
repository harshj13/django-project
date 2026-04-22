# Django Assignment 3 - Student Portal

This project is built with Django and SQLite3.

## Features
- Bootstrap based UI templates
- User registration
- Login and logout system
- SQLite3 database (default Django database)

## Setup and Run
1. Create virtual environment:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Apply migrations:
   ```bash
   python manage.py migrate
   ```
4. Start server:
   ```bash
   python manage.py runserver
   ```
5. Open in browser:
   - Home: `http://127.0.0.1:8000/`
   - Register: `http://127.0.0.1:8000/register/`
   - Login: `http://127.0.0.1:8000/login/`
