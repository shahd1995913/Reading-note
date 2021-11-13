# Django
## With Django,  can take web applications from concept to launch in a matter of hours. Django takes care of much of the hassle of web development, so you can focus on writing your app without needing to reinvent the wheel. It’s free and open source.
### Install the Django code
- [x]  $ python -m pip install Django
- [x] $ git clone https://github.com/django/django.git
- [x] $ python -m pip install -e django/ 
- [x] When  want to update your copy of the Django source code, run the command git pull from within the django.
- [x] $ python -m django --version ===> 4.1.dev20211112120556


# In Django app
## A public site that lets people view polls and vote in them and An administrative interface that lets you add, change and delete polls.
### Creating a project
- [x]  django-admin startproject mysite
- [x] verify your Django project works : python manage.py runserver
- [x] Creating the Polls app : python manage.py startapp polls



## ==> The path() function is passed four arguments, two required: route and view, and two optional: kwargs, and name.

### 1. path() argument: route is a string that contains a URL pattern.

### 2. path() argument: view : When Django finds a matching pattern, it calls the specified view function with an HttpRequest object as the first argument and any “captured” values from the route as keyword arguments.

### 3. path() argument: kwargs : Arbitrary keyword arguments can be passed in a dictionary to the target view.

### 4. path() argument: name : Naming your URL lets you refer to it unambiguously from elsewhere in Django.

- [x]  A clean, elegant URL scheme is an important detail in a high-quality web application
- [x] Django’s template language is designed to strike a balance between power and ease. It’s designed to feel comfortable and easy-to-learn to those used to working with HTML, like designers and front-end developers
- [x] Django also provides a way to generate forms from your existing models and use those forms to create and update data.
- [x] Django comes with a full-featured and secure authentication system. It handles user accounts, groups, permissions and cookie-based user sessions.