#python django
django project

#install Env
python -m venv Env
active Env -> cd Env\Script\activate.bat

*deactivate (Env)
deactivate

#install django
pip install django

*upgrade pip
python -m pip install --upgrade pip

#install django-admin
django-admin startproject mywebsite

->cd mywebsite
#run server
python manage.py runserver

--->http://127.0.0.1:8000

#buat project blog
python manage.py startproject blog

# Django 2.0 >
$ python -m django --version

#buat project polls
python manage.py startproject polls
https://docs.djangoproject.com/en/2.0/intro/tutorial01/