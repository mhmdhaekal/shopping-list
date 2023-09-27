release: python manage.py reset_db --noinput && python manage.py migrate --noinput
web: gunicorn shopping_list.wsgi
