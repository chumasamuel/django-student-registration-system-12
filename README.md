# PRACTICAL 12 — Django Models, Admin and Validated Forms

**Name:** Samuel Fernando Chuma  
**Register Number:** ____________________  
**Practical Number:** 12

## Run

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Open:
- http://127.0.0.1:8000/
- http://127.0.0.1:8000/students/
- http://127.0.0.1:8000/admin/

## Validation

Register number format: `STU` + exactly 7 digits, e.g. `STU2026001`.

Semester must be between 1 and 8.

The project includes CSRF protection, success messages, newest-first listing, Django admin search/filters, and automated tests.

Run tests:

```bash
python manage.py test
```
