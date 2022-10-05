# Please read this file

    Add this new file

    

functional programming vs oop

static language vs dynamic language

MVT (Model View Template)
MVC (Model View Controller)

Web Architecture Design- HTML Serve Design, Data Serve Design(API)-Django

https://pypi.org/ (install libraries)

python -V (check version)

python -m venv env (create virtual env)

env\Scripts\activate (activate virtual env)

pip install Django (install it)

open- microsoft sql- (LocalDb)\MSSQLLocalDB

pip install mssql-django

django-admin startproject -projectname-

dirr- check directory

cd blog - change directory

ctrl+c -break the server

python manage.py startapp -projectapp

-Microsoft SQL-Setting.py
DATABASES = {

    'default': {
        'ENGINE': 'mssql',
        'NAME': 'Blog',
        'HOST': '(LocalDb)\MSSQLLocalDB',
        'PORT':'',
        'USER':'',
        'PASSWORD':'',
        'OPTION':{
            'driver': "ODBC Drive 17 for SQL Server",
        }
    }

}

python manage.py makemigrations

python manage.py migrate -keep track our sql database that changes

python manage.py createsuperuser

linkedin learn- build my portfolio with django

https://docs.djangoproject.com/en/4.1/intro/tutorial02/

