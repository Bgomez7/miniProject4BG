# miniproject4BGomez

INF601 Advanced Programming with Python, Brayan Gomez

## Description
This project uses Django to build a basic poll web app. 

## Pip install instructions
Please run the following:
```
pip install -r requirements.txt
```
## How to run
This will create SQL entries that will populate the database.
```
python manage.py makemigrations
```
Apply migrations
```
python manage.py migrate
```
Create an administrator login to access the /admin site
```
python manage.py createsuperuser
```
Type the following to start a local server:
```
python manage.py runserver
```