# Neighbourhood-App

# Author

Sandrine TUYIZERE

# Description

This is a neighborhood app where a user must signup first, be able to join a hood owned by the hood admin, and once you join a hood or create your own hood, one can see businesses and posts in only that wood they belong to.

# Prerequisites

What things you need to install the software and how to install them install all this command in terminal pip

* python3.6 -m venv --without-pip virtual
* source virtual/bin/activate
* curl https://bootstrap.pypa.io/get-pip.py | python
* python manage.py createsuperuser
* pip install Pillow
* pip install psycopg2
* pip install django-tinymce
* pip install django-registration==2.4.1
* pip install django-bootstrap4
* python manage.py makemigrations hoodapp
* python3.6 manage.py migrate
* python3.6 -m pip install gunicorn
* pip install whitenoise

# Running the tests

Explain how to run the automated tests for this system in able to run this application you need first to run the server by using: