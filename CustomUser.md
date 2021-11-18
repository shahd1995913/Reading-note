# Django Best Practices: Custom User Model
## The official Django documentation highly recommends using a custom user model instead. This provides far more flexibility down the line so, as a general rule.
## Setup : to start, create a new Django project from the command line.

### 1. create and navigate into a dedicated directory called accounts for our code
### 2. install Django
### 3. make a new Django project called config
### 4. make a new app accounts
### 5. start the local web server
## The commands to run:

- [x] $ cd ~/Desktop
- [x] $ mkdir accounts && cd accounts
- [x] $ pipenv install django~=3.1.0
- [x] $ pipenv shell
- [x] (accounts) $ django-admin.py startproject config .
- [x] (accounts) $ python manage.py startapp accounts
- [x] (accounts) $ python manage.py runserver
##  We can  run makemigrations and migrate for the first time to create a new database that uses the custom user model.

- [x] (accounts) $ python manage.py makemigrations accounts
- [x] (accounts) $ python manage.py migrate

## Superuser
### It's helpful to create a superuser that we can use to log in to the admin and test out log in/log out. 
### On the command line type the following command and go through the prompts.
- [x] (accounts) $ python manage.py createsuperuser
### Custom User Model : Creating our initial custom user model requires four steps:

- [x] update config/settings.py
- [x] create a new CustomUser model
- [x] create new UserCreation and UserChangeForm
- [x] update the admin
- [x] Within INSTALLED_APPS add accounts at the bottom. Then at the bottom of the entire file, add the AUTH_USER_MODEL config.
