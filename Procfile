release: python manage.py reset_db --noinput && python manage.py migrate --noinput && python manage.py collectstatic --noinput --clear
web: gunicorn shopping_list.wsgi
