* Installation and first steps see [here](https://docs.djangoproject.com/en/4.1/intro/install/)
* For start server - python manage.py runserver
* sudo gunicorn -b 0.0.0.0:8000 --pythonpath /home/box/web/ask ask.wsgi:application