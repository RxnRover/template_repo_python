..
    These are examples of badges you might want to add to your README:
    please update the URLs accordingly

     .. image:: https://api.cirrus-ci.com/github/<USER>/template_repo_python.svg?branch=main
         :alt: Built Status
         :target: https://cirrus-ci.com/github/<USER>/template_repo_python
     .. image:: https://readthedocs.org/projects/template_repo_python/badge/?version=latest
         :alt: ReadTheDocs
         :target: https://template_repo_python.readthedocs.io/en/stable/
     .. image:: https://img.shields.io/coveralls/github/<USER>/template_repo_python/main.svg
         :alt: Coveralls
         :target: https://coveralls.io/r/<USER>/template_repo_python
     .. image:: https://img.shields.io/pypi/v/template_repo_python.svg
         :alt: PyPI-Server
         :target: https://pypi.org/project/template_repo_python/
     .. image:: https://img.shields.io/conda/vn/conda-forge/template_repo_python.svg
         :alt: Conda-Forge
         :target: https://anaconda.org/conda-forge/template_repo_python
     .. image:: https://pepy.tech/badge/template_repo_python/month
         :alt: Monthly Downloads
         :target: https://pepy.tech/project/template_repo_python
     .. image:: https://img.shields.io/twitter/url/http/shields.io.svg?style=social&label=Twitter
         :alt: Twitter
         :target: https://twitter.com/template_repo_python

.. image:: https://api.cirrus-ci.com/github/RxnRover/template_repo_python.svg?branch=main
    :alt: Built Status
    :target: https://cirrus-ci.com/github/RxnRover/template_repo_python

.. image:: https://img.shields.io/badge/-PyScaffold-005CA0?logo=pyscaffold
    :alt: Project generated with PyScaffold
    :target: https://pyscaffold.org/

|

template_repo_python
====================

    TemplateRepoPython provides a single interface to use many reaction optimization
    algorithms.

- optimization algorithms have different user interfaces, from web portals to
  software-only interfaces
- when targeting reaction optimization, the algorithms are expected to be used
  in the lab, likely by someone without much programming experience
- trying different algorithms means potentially learning multiple installation
  methods, user interfaces, and data formats
- TemplateRepoPython aims to provide a single software interface that can provide access
  to many different reaction optimization algorithms
- this allows users to program to a single software interface, simplifying the
  development of user-friendly tools and interfaces to lower the barrier of
  entry into reaction optimization

.. _template_repo_python_overview_install:

Installation and Usage
----------------------

TemplateRepoPython is a Python-based library available for installation from PyPI using
``pip``:

.. code-block:: bash

    pip install template_repo_python

API Usage
---------

For API usage, see :ref:`api_usage`.

.. _pyscaffold-notes:

Making Changes & Contributing
-----------------------------

This project uses pre-commit_, please make sure to install it before making any
changes or you will not be able to make commits!!!

.. code-block:: bash

    pip install pre-commit
    cd template_repo_python
    pre-commit install

It is a good idea to update the hooks to the latest version:

.. code-block:: bash

    pre-commit autoupdate

Don't forget to tell your contributors to also install and use pre-commit.

.. _pre-commit: https://pre-commit.com/

Note
----

This project has been set up using PyScaffold 4.3.1. For details and usage
information on PyScaffold see https://pyscaffold.org/.
