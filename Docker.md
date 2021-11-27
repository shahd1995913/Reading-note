# A Beginner's Guide to Docker
##  Install Docker
- [x]  $ docker --version
- Docker version 19.03.5, build 633a0ea
- [x] $ docker-compose --version
- docker-compose version 1.24.1, build 4667896b
- [x] docker run hello-world
### A good command to inspect Docker is docker info.
## Images and Containers : 
### - Images and containers are the two fundamental concepts to grasp when you start with Docker. 
###  - An image is a snapshot in time of what a project contains.
###  -  A container is a running instance of the image.
## To create an example_project that we’ll put in  directory. Don’t forget the period . at the end of the command here.
- [x] (djangoapp) $ django-admin startproject example_project .
### And then we can use runserver to start this new Django project.
- [x] (djangoapp) $ python manage.py runserver
## Dockerized Django
- [x] $ touch Dockerfile
- [x] $ touch docker-compose.yml

##  Library Website and API
### Django REST Framework works alongside the Django web framework to create web APIs. We cannot build a web API with only Django Rest Framework; it always must be added to a project after Django itself has been installed and configured.
### 1.  (library) $ django-admin startproject config .
### 2. (library) $ python manage.py makemigrations books
### 3. (library) $ python manage.py migrate
### 4. (library) $ python manage.py createsuperuser
### 5. (library) $ python manage.py runserver
### 6. (library) $ python manage.py startapp books


