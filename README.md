# django-dummy-project
Django tutorial from https://www.w3schools.com/django/index.php

#Creating a dedicated Virtual environment for my project
py -m venv django-dummy-project

#Activate the environment
.\Scripts\activate

#Install Django
py -m pip install Django

#Creating project
django-admin startproject helloworld

#Creating app
py manage.py startapp members

#Run Django project
py manage.py runserver

#Creating DB files
py manage.py makemigrations members

#Running DB files
py manage.py migrate

#Access the members page
http://localhost:8000/members/