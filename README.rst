Polls
=====

This is a basic poll application.

Requirements
------------

- Python 2.7.8
- PostgreSQL 9.3.5
- pip 1.5.6

Setup
-----

.. code-block:: bash

    $ pip install -r requirements/local.txt
    $ ./manage.py migrate --settings=mysite.settings.local
    $ ./manage.py createsuperuser --settings=mysite.settings.local

Usage
-----

.. code-block:: bash

    $ ./manage.py runserver --settings=mysite.settings.local

Test
----

.. code-block:: bash

    $ ./manage.py test --settings=mysite.settings.test

Source code check
-----------------

.. code-block:: bash

    $ flake8 --exclude=./mysite/polls/migrations/* .
