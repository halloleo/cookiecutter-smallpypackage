Cookiecutter PyPackage
======================

[Cookiecutter](https://github.com/audreyr/cookiecutter) template for a
Small Python package, forked from
[audreyr/cookiecutter-pypackage](https://github.com/audreyr/cookiecutter-pypackage).

Features
--------

This template is just a lot smaller than  the original
[audreyr/cookiecutter-pypackage](https://github.com/audreyr/cookiecutter-pypackage):

- No docs
- All text files are markdown

Quickstart
----------

Install the latest Cookiecutter if you haven\'t installed it yet (this
requires Cookiecutter 1.4.0 or higher):

    pip install -U cookiecutter

Generate a Python package project:

    cookiecutter https://github.com/briggySmalls/cookiecutter-pypackage.git

Then:

-   Create a repo and put it there.
-   Add the repo to your [Travis-CI](http://travis-ci.org/) account.
-   Install the dev requirements into a virtualenv.
    (`pipenv install --dev`)
-   [Register](https://packaging.python.org/distributing/#register-your-project)
    your project with PyPI.
-   Run the Travis CLI command [travis encrypt \--add
    deploy.password]{.title-ref} to encrypt your PyPI password in Travis
    config and activate automated deployment on PyPI when you push a new
    tag to master branch.
-   Add the repo to your [ReadTheDocs](https://readthedocs.io/)
    account + turn on the ReadTheDocs service hook.
-   Release your package by pushing a new tag to master.
-   Get your code on! 😎 Add your package dependencies to your setup.py
    as you go, and lock them into your virtual environment with
    `pipenv install`.
-   Activate your project on [pyup.io](https://pyup.io/).

For more details, see the [cookiecutter-pypackage
tutorial](https://briggysmalls.github.io/cookiecutter-pypackage/tutorial.html).
