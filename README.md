# Image-Processing-App
This is a minimal Django 1.8 project. It was created with these steps:

Manually install Django and other dependencies
pip freeze > requirements.txt

django-admin startproject project .

Update project/settings.py to configure SECRET_KEY, DATABASE and STATIC_ROOT entries

./manage.py startapp welcome, to create the welcome page's app

# From this initial state you can:

Create new Django apps

Remove the welcome app

Rename the Django project

Update settings to suit your needs

Install more Python libraries and add them to the requirements.txt file
Special files in this repository



#  To run this project in your development machine, follow these steps:

If everything is alright, you should be able to start the Django development server:
got to your project directory and type the command:

python manage.py runserver

Open your browser and go to http://127.0.0.1:8000/app-name.

