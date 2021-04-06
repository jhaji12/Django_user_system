# Django_user_system
PyCharm can be Used to run this locally <br>
Type the following commands in Terminal
Check whether python is installed in your PC <br>
```python --version```<br>
To Create Django-environment<br>
```python3 -m venv env```<br>
```env\scrpits\activate```<br>
```pip install django== 3.0.4```<br>
```django-admin.py startproject hello_django .```<br>
```python manage.py startapp users ```<br>
Add the new app to the INSTALLED_APPS list in settings.py<br>
```  
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',

    'users',
]
```
Clone this project <br>
```git clone <link of the repository>```<br>
```python manage.py makemigration```<br>
```python manage.py migrate```<br>
To create superuser <br>
```python manage.py createsuperuser```<br>
to run <br>
``` manage.py runserver```<br>
You will get an IP address click and go to successful deployment page of django <br>
Edit the URL and add ```\admin``` at the end <br>
you will reach to Django-administration page <br>
Now you can add users and give permissions to them.



