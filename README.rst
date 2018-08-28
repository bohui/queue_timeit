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

.. |docs| image:: https://readthedocs.org/projects/queue_timeit/badge/?style=flat
    :target: https://readthedocs.org/projects/queue_timeit
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/bohui/queue_timeit.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/bohui/queue_timeit

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/bohui/queue_timeit?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/bohui/queue_timeit

.. |requires| image:: https://requires.io/github/bohui/queue_timeit/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/bohui/queue_timeit/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/bohui/queue_timeit/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/bohui/queue_timeit

.. |version| image:: https://img.shields.io/pypi/v/queue_timeit.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/queue_timeit

.. |commits-since| image:: https://img.shields.io/github/commits-since/bohui/queue_timeit/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/bohui/queue_timeit/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/queue_timeit.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/queue_timeit

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/queue_timeit.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/queue_timeit

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/queue_timeit.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/queue_timeit


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install queue_timeit

Documentation
=============

https://queue_timeit.readthedocs.io/

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
