Django - Ember.js tutorial for using JSON web token (JWT) authentication
======================================================================

A sample Ember.js client app with registration and login routes and Django REST API backend server made with django-rest-framework.

Installation:
-------------
    $ virtualenv --python=$(which python3)
    $ git clone https://github.com/davideferre/django-ember-jwt-tutorial.git
    $ cd django-ember.js-jwt-tutorial
    $ pip install -r requirements.txt
    $ python3 manage.py migrate
    $ python3 manage.py createsuperuser
    $ python3 manage.py runserver

In a separate shell:
    $ npm install
    $ bower install
    $ ember serve

Usage:
------
Run a browser and you can find the front-end app on http://localhost:4200 and the REST API server on http://localhost:8000 with admin dashboard on http://localhost:8000/admin
