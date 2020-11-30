# Download (Windows)

```
mkdir authapi
cd authapi
python -m venv env
git clone https://github.com/luterien/django-auth-test
env\Scripts\activate
cd django-auth-test
```

# Installation (Windows)

```
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver 0.0.0.0:8000
```
