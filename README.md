Employee Management System 🏢

A full-stack Employee Management System built with Django (Python) and PostgreSQL.
This web application helps organizations manage employees, track work assignments, attendance, and internal communication efficiently.

🚀 Features

Authentication & Authorization

Secure login/registration for Admin and Employees.

Admin Functionality

Add, update, and remove employees.

Publish and manage notices.

Track and manage attendance.

Assign tasks and monitor progress.

Employee Functionality

View assigned tasks and notices.

Update work status.

Submit requests to admin.

🛠️ Tech Stack

Backend: Django (Python)

Frontend: HTML, CSS, Tailwind (with Django templates)

Database: PostgreSQL

Other Tools: Pipenv (Virtual Environment), Git/GitHub

⚡ Getting Started
Prerequisites

Python (>= 3.9 recommended)

PostgreSQL

Pipenv (for virtual environment)

Setup Instructions

Clone the repository:

git clone https://github.com/<your-username>/EmployeeManagementSys.git
cd EmployeeManagementSys


Create & activate virtual environment:

pip install pipenv
pipenv shell


Install dependencies:

pip install django psycopg2


Configure your database in settings.py:

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'your_db_name',
        'USER': 'your_db_user',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}


Run migrations:

python manage.py makemigrations
python manage.py migrate


Start the development server:

python manage.py runserver


Open in browser:

http://127.0.0.1:8000/
