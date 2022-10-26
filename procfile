web: gunicorn portfolio.wsgi --log-file -
web: python manage.py collectstatic --noinput
web: python manage.py makemigrations
web: python manage.py migrate
web: python manage.py runserver