# Django-Signals

Django Signals & Custom Python Classes
This repository contains examples demonstrating:

The behavior of Django signals (synchronous execution, threading behavior, and database transactions).

A custom Python class (Rectangle) that supports iteration.

Table of Contents
Django Signals

Are Django signals executed synchronously?

Do Django signals run in the same thread as the caller?

Do Django signals run in the same database transaction?

Custom Python Class

Setup & Execution

License




##
Setup & Execution
1. Clone the Repository

git clone https://github.com/your-username/django-signals-python-classes.git
cd django-signals-python-classes
#2. Setup a Virtual Environment

python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

#3. Install Dependencies


pip install django

#4. Run Django Shell for Signal Tests

python manage.py shell

Then manually run the signal-related test scripts.

#5. Run the Custom Class Script

python rectangle.py

License
This project is licensed under the MIT License.
