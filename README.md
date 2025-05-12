A room booking system
=====
The web application is build with python Django framwork along with SQLite3 database. It has basic login system since the booking have to be done with authentication. A admin account is created by default, with username: admin, and password: admin. The administrator have the access to directly manipulate team and users. 

## Requirements
1. Python 3
2. Install SQLite3 
3. Recommend SQLite browser 



## Setup
1. Install django and packages
```
$ pip install django
$ pip install django-wtf
$ pip install django-sqlalchemy
$ pip install django-migrate
$ pip install django-login
```
2. Define the project
```
$ export django_APP=lab2.py
```

3. Init the database
```
$ django db init
```

## Migrating data
1. Run the migration command from the project directory to create tables
```
$ django db upgrade
```
2. Populate the database with dummy data(if weren't populated after migration)
```
$ python populate.py
```

# Running
1. Run the django application from the project directory, running on localhost
```
$ django run
```
2. Open the app in browser: [localhost](http://127.0.0.1:5000/)
