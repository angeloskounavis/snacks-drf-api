# LAB - Class 31

## Project: Django REST Framework & Docker

    ## Author: Angelos Kounavis

### Description

* Django app that allows users to input homes with the following attributes: (owner, street address, city, state, square feet, and description). The site acts like an API and returns JSON data when queried.

### Setup

- Do the mkdir with file name
- Create and activate virtual environment.
- Run `pip install -r requirements.txt`
- Run `python manage.py makemigrations` and `python manage.py migrate`.
- Run `python manage.py runserver` and copy the localhost URL with `/admin` at the end.
- Log-in to the Django admin portal with the username "***admin***" and password "***12345***".
- dd, delete, or modify a home entry.
- Run `docker-compose up` to create a Docker container (not sure if that's the correct terminology).

### Tests

* Run tests with the command: `python manage.py test`.
* All 6 tests passing!

## Contributors
-Ricardo
-Aubrey
-Dylan
