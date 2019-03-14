=============================
package
=============================

.. image:: https://badge.fury.io/py/repo.svg
    :target: https://badge.fury.io/py/repo

.. image:: https://travis-ci.org/hackoregon/repo.svg?branch=master
    :target: https://travis-ci.org/hackoregon/repo

Your project description goes in here

Documentation
-------------

The full documentation is at http://hackoregon.github.io/repo

Quickstart
----------

Install package::

    pip install repo

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'app.apps',
        ...
    )

Add package's URL patterns:

.. code-block:: python

    from app import urls as app_urls


    urlpatterns = [
        ...
        url(r'^', include(app_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
