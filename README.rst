===============================
Calc
===============================


.. image:: https://img.shields.io/pypi/v/calc.svg
        :target: https://pypi.python.org/pypi/calc

.. image:: https://img.shields.io/travis/lgiordani/calc.svg
        :target: https://travis-ci.org/lgiordani/calc

.. image:: https://readthedocs.org/projects/calc/badge/?version=latest
        :target: https://calc.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status

.. image:: https://pyup.io/repos/github/lgiordani/calc/shield.svg
     :target: https://pyup.io/repos/github/lgiordani/calc/
     :alt: Updates


A small project used to introduce TDD


* Free software: MIT license
* Documentation: https://calc.readthedocs.io.


Setup
-----
Please do the following steps to install the dependencies and make sure you are ready to go:

1. Clone this repository

2. Install requirements

pip install -r requirements/dev.txt

3. Check your setup

Check that pytest is installed properly:

py.test -svv

This command should show a message about the number of tests passed (there should be no failures).

4. Fetch tags from the remote

git fetch --all --tags --prune

5. (Optional) Set up branches

During the workshop, I will ask you to checkout different tagged commits as starting points for different exercises.

The command for checking out a tag is:

git checkout tags/<tag-name> -b <branch-name>


Features
--------

* TODO

Credits
---------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage

