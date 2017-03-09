![alt tag](https://cloud.githubusercontent.com/assets/3624858/23752368/0b926366-04fb-11e7-9de6-f588df5fe1cb.png)

## Django code workflow

Describes the basics steps required to get a django-app up and running.

 Make sure django is installed
```
pip install django
```
Create a django project
```
django-admin startproject project
```
The functionality of web-app can be divided into smaller apps.
```
cd project
python manage.py startapp app
```
The project the structure
```
project/
|-- app
|   |-- admin.py
|   |-- apps.py
|   |-- __init__.py
|   |-- migrations
|   |   `-- __init__.py
|   |-- models.py
|   |-- tests.py
|   `-- views.py
|-- db.sqlite3
|-- manage.py
`-- project
    |-- __init__.py
    |-- settings.py
    |-- urls.py
    |-- wsgi.py
```
Include the create app in the main settings
```
```
Run migrations and start the development server
```
python manage.py migrate
python manage.py runserver
```
Create a simple view
```
```
Create route for app
```
```
Include the route
```
```
Visit the page we created.
```
```

