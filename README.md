# hospital

Requirements: poetry

To run the app:

pipenv install

pipenv shell

./build.sh

gunicorn mysite.wsgi:application
