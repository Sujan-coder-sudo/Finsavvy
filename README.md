# Finsavvy
Finsavvy your ai companion in finance

How to use:

pip install django
pip install psycopg2

pip install psycopg2-binary
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'your_database_name',
        'USER': 'your_database_user',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',  # or the IP address of your PostgreSQL server
        'PORT': '5432',  # Default PostgreSQL port
    }
}
edit in settings.py

python manage.py makemigrations
python manage.py migrate
