web: gunicorn app.wsgi --log-file -
release: python manage.py collectstatic
release: python manage.py migrate
