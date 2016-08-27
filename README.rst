cookiecutter-terraform-module
==================================================

Cookiecutter template for terraform module.

|Build Status|

Requirements
------------

Cookiecutter (>=1.4.0) (https://github.com/audreyr/cookiecutter)

How to
------

You can create new project of Cookiecutter template as follows.

.. code:: bash

    $ cookiecutter gh:FGtatsuro/cookiecutter-terraform-module
    ...
    project_name [Name of generated project]: test-project
    project_description [Description of generated project]: Test Project
    year [2016]:
    author [FGtatsuro]:
    ...
    $ cd use-generated-template
    $ ls -1a
    .
    ..
    LICENSE
    README.rst

You can overwrite default value of the field prompt asks with `~/.cookiecutterrc`.
It's better to overwrite 'author' field with your Github username.

.. code:: bash

    $ cat ~/.cookiecutterrc
    default_context:
        author: "FGtatsuro"

    $ cookiecutter gh:FGtatsuro/cookiecutter-terraform-module
    ...
    author [FGtatsuro]:
    ...

.. |Build Status| image:: https://travis-ci.org/FGtatsuro/cookiecutter-terraform-module.svg?branch=master
   :target: https://travis-ci.org/FGtatsuro/cookiecutter-terraform-module

