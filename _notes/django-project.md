## Create django prject

```
  django-amin.py startproject <project>
```
Django creats a folder named <project>
<project> will be used in  manage.py, __init__.py, settings.py and urls.py

## Project structure

- manage.py [DO NOT Edit]
  run commands

- __init__.py  [DO NOT Edit]
  Tell Python that the folder contains Python files

- wsgi.py [DO NOT Edit]
  Provides a hook for web server

- settings.py
  Configures Django

- urls.py
  Routes request based on URL


## Create python venv 
```
  python3 -m venv venv3
```

## Run Project
```
  python3 manage.py runserver
```

## Login
```
http://localhost:8000/admin/
admin / admin
```

## Django Apps
- An app is a folder with Python files
- An app is a component in Django

Django creates some apps by defult, those apps were defined in setting.py 
```
  INSTALLED_APPS = [
    ...
  ]
```


## Create App
```
  python manage.py startapp <appname>
```
add <appname> into INSTALLED_APPS in settings.py

Applicaton files
- apps.py:  config and initialization
- modles.py:  Data layer
- admin.py: amdinistrator interface
- ursl.py: URL routing
- views.py: controller layer
- tests.py: test the app
- migrations/ : migration files

