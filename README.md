# django-oauth
Start project oauth using django.
---------------------------------------------------------
Environment
pip install django
pip install django-allauth

asgiref==3.3.1
certifi==2020.12.5
cffi==1.14.4
chardet==4.0.0
cryptography==3.3.1
defusedxml==0.6.0
Django==3.1.5
django-allauth==0.44.0
idna==2.10
oauthlib==3.1.0
pycparser==2.20
PyJWT==2.0.1
python3-openid==3.2.0
pytz==2020.5
requests==2.25.1
requests-oauthlib==1.3.0
six==1.15.0
sqlparse==0.4.1
urllib3==1.26.2
-----------------------------------------------------------
Step command :
(env) pip install django 
(env) django-admin startproject my_site
(env) cd my_site
(env) python manage.py startapp login_page
(env) python manage.py migrate
(env) python manage.py runserver
(env) pip install django-allauth

(env) python manage.py makemigrations
(env) python manage.py migrate
