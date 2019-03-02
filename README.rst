========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-cookiecutter/badge/?style=flat
    :target: https://readthedocs.org/projects/python-cookiecutter
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/mvmma/python-cookiecutter.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/mvmma/python-cookiecutter

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/mvmma/python-cookiecutter?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/mvmma/python-cookiecutter

.. |requires| image:: https://requires.io/github/mvmma/python-cookiecutter/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/mvmma/python-cookiecutter/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/mvmma/python-cookiecutter/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/mvmma/python-cookiecutter

.. |version| image:: https://img.shields.io/pypi/v/cookiecutter.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/cookiecutter

.. |commits-since| image:: https://img.shields.io/github/commits-since/mvmma/python-cookiecutter/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/mvmma/python-cookiecutter/compare/v0.0.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/cookiecutter.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/cookiecutter

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/cookiecutter.svg
    :alt: Supported versions
    :target: https://pypi.org/project/cookiecutter

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/cookiecutter.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/cookiecutter


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install cookiecutter

Documentation
=============


https://python-cookiecutter.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
