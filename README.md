# Personal Finance Tracker Web App (Django)

This is a Django-based personal finance tracker that helps users manage their income, expenses, and financial goals.

## ✅ Features
- User Registration & Authentication (Login/Logout)
- Add, Edit, Delete Income & Expense Transactions
- Set Financial Goals with Deadlines
- Dashboard displaying Total Income, Total Expenses, Net Savings, and Goal Progress
- Export Transactions to Excel (XLSX) via Django Admin Panel
- Responsive Design using Bootstrap

## ✅ Tech Stack
- Django (Python Web Framework)
- SQLite (Database)
- Bootstrap (Front-End)
- django-import-export (Data Export)
- HTML, CSS

## ✅ Installation Guide
1. Clone the repository:
```bash
git clone https://github.com/Sakshamjain2005/finance-tracker-django.git

2.cd finance-tracker-django
3.python -m venv venv
.\venv\Scripts\activate
4.pip install -r requirements.txt
5.python manage.py makemigrations
python manage.py migrate
6.python manage.py createsuperuser
7.python manage.py runserver
