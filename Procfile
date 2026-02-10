release: python manage.py migrate --noinput && python manage.py collectstatic --noinput
web: uwsgi ./etc/uwsgi.ini
worker: python manage.py db_worker
