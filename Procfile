web: gunicorn proshift.wsgi && python manage.py makemigrations api && python manage.py migrate && python manage.py makemigrations dashboard && python manage.py migrate && python manage.py makemigrations  && python manage.py migrate &&  python manage.py runserver