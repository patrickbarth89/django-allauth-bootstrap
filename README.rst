==========================
Welcome to django-allauth!
==========================

.. image:: https://badge.fury.io/py/django-allauth.png
   :target: http://badge.fury.io/py/django-allauth

.. image:: https://travis-ci.org/pennersr/django-allauth.png
   :target: http://travis-ci.org/pennersr/django-allauth

.. image:: https://img.shields.io/pypi/v/django-allauth.svg
   :target: https://pypi.python.org/pypi/django-allauth

.. image:: https://coveralls.io/repos/pennersr/django-allauth/badge.png?branch=master
   :alt: Coverage Status
   :target: https://coveralls.io/r/pennersr/django-allauth

.. image:: https://pennersr.github.io/img/bitcoin-badge.svg
   :target: https://blockchain.info/address/1AJXuBMPHkaDCNX2rwAy34bGgs7hmrePEr

Integrated set of Django applications addressing authentication,
registration, account management as well as 3rd party (social) account
authentication.

Home page
  http://www.intenct.nl/projects/django-allauth/

Source code
  http://github.com/pennersr/django-allauth

Mailinglist
  http://groups.google.com/group/django-allauth

Documentation
  https://django-allauth.readthedocs.io/en/latest/

Stack Overflow
  http://stackoverflow.com/questions/tagged/django-allauth

Cross-Selling
=============

If you like this, you may also like:

- django-trackstats: https://github.com/pennersr/django-trackstats
- netwell: https://github.com/pennersr/netwell

This fork
=========

This fork contains django-allauth example's Bootstrap & Uniform templates repackaged as separate Django applications for easy installation.

Usage:

    pip install https://github.com/yuriiz/django-allauth-bootstrap-uniform

and

    INSTALLED_APPS = [
        ...

        'bootstrapform',

        'allauthbootstrap',

        'allauth',

        ...
    ]

or

    INSTALLED_APPS = [
        ...

        'allauthuniform',

        'allauth',

        ...
    ]
