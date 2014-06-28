web: /users/apple/django-env/bin/gunicorn_django --workers=4 --bind=0.0.0.0:$PORT /users/apple/django-env/projectxweb/projectxweb/settings.py
worker: /users/apple/django-env/bin/python /users/apple/django-env/projectxweb/manage.py celeryd -E -B --loglevel=INFO
