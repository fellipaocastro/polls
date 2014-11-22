Polls
=====

This is a basic poll application.

Requirements
------------

- Python 2.7.8
- pip 1.5.6

Local setup
-----------

.. code-block:: bash

    $ pip install -r requirements/local.txt
    $ ./mysite/manage.py migrate
    $ ./mysite/manage.py createsuperuser

Usage
-----

.. code-block:: bash

    $ ./mysite/manage.py runserver

Test
----

.. code-block:: bash

    $ ./mysite/manage.py test

Source code check
-----------------

.. code-block:: bash

    $ flake8 --exclude=./mysite/polls/migrations/* .
