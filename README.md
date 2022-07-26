cd django-user-management/
python -m venv venv
source venv/bin/activate
python -m pip install --upgrade pip
python -m pip install django==4.0.2
django-admin startproject awesome_website
cd awesome_website/
python manage.py startapp users


##add below to settings.py
INSTALLED_APPS = [
    'users',


python manage.py migrate
python manage.py runserver

##comment AUTH_PASSWORD_VALIDATORS section in settings.py

##create mariusz/mariusz user

pwd
/home/mariusz/python/workspace/django-user-management/awesome_website
mkdir users/templates
mkdir users/templates/users
mkdir users/templates/registration
touch users/templates/base.html