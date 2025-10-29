# Fake Movie Database

## Commands Used

cd ~/projects/fake-movie-database
python3 -m venv venv
source venv/bin/activate
pip install django
django-admin startproject fake_movie_database .
python manage.py migrate
python manage.py runserver
