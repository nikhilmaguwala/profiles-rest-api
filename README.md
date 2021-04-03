# Profiles REST API 

Profiles REST API using Python, Django, REST-Framework.

## To Run Vagrant Server

```bash
Vagrant init ubuntu/bionic64 # Initialize Vagrant server with ubuntu
Vagrant up # Starts the ubuntu/bionic64 OS
Vagrant ssh # Switch to Vagrant's OS Terminal
Cd /vagrant # Locate to vagrant folder
```

## Creating Python Virtual Environment

```bash
python -m venv ~/env  # creating virtual environment named as env
source ~/env/bin/activate # To Activate Virtual Environment
Deactivate # To Deactivate Virtual Environment
pip install -r requirements.txt # Installing Requirements from txt file
django-admin.py startproject profiles_project . # Creating new Python-Django Project
python manage.py startapp profiles_api # Creating new Python-Django App
python manage.py runserver 0.0.0.0:8000 # Starting Python - Django Server
```

## Creating Migrations

```bash
python manage.py makemigrations profiles_api  # To create migrations file
python manage.py migrate # To migrate server
python manage.py createsuperuser # For creating super user
```