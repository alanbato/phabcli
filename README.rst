========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - |
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/phabcli/badge/?style=flat
    :target: https://readthedocs.org/projects/phabcli
    :alt: Documentation Status

.. |codecov| image:: https://codecov.io/gh/alanbato/phabcli/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/alanbato/phabcli

.. |version| image:: https://img.shields.io/pypi/v/phabcli.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/phabcli

.. |wheel| image:: https://img.shields.io/pypi/wheel/phabcli.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/phabcli

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/phabcli.svg
    :alt: Supported versions
    :target: https://pypi.org/project/phabcli

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/phabcli.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/phabcli

.. |commits-since| image:: https://img.shields.io/github/commits-since/alanbato/phabcli/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/alanbato/phabcli/compare/v0.1.0...master



.. end-badges

Phabricator for your terminal.

* Free software: Apache Software License 2.0

Installation
============

::

    pip install phabcli

You can also install the in-development version with::

    pip install https://github.com/alanbato/phabcli/archive/master.zip


Documentation
=============


https://phabcli.readthedocs.io/


Development
===========

To run all the tests run::

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
