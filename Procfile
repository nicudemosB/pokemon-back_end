release: python manage.py makemigrations
--no-input
release: python manage.py migrate --no-input

web: gunicorn pokemon_rest_api.wsgi
