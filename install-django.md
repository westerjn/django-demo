# create python venv
python -m venv env
# start python venv
env\Scripts\activate
# install django
pip install django
# create a django app
django-admin startproject django_app
# change to django web folder
cd django_app
# create web files
python manage.py startapp hello
# launch server
python manage.py runserver
# create user database
python manage.py migrate
# create authenticated users
python manage.py createsuperuser
# create hello/views.py
# create templates/hello/index.html
# update urls.py

#
# url -- https://www.youtube.com/watch?v=LQTMqGns7Co
