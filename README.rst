-------------------------------------------
Fork of the official ``readthedocs/sphinx_rtd_theme`` repo.
-------------------------------------------

``work in progress...``

^^^^^^^^^^^^^^^^
Original repo
^^^^^^^^^^^^^^^^

* https://github.com/readthedocs/sphinx_rtd_theme

^^^^^^^^^^^^^^^^
About this Fork
^^^^^^^^^^^^^^^^

Goal is to...

* create a ``pip`` installable theme that users can download locally

Steps to use once complete:
 
* Checkout the official Python docs
* Edit ``cpython/Doc/config.py`` Sphinx Configuration file to reference this new ``python_rtd_theme``
* Then build the official Python Docs locally, get a website with a true TOC ("Table of Contents") sidebar.

^^^^^^^^^^^^
Related Repos
^^^^^^^^^^^^

* https://github.com/python-docs-101/Python-Documentation-Theme-Fork
  
  * ``cpython`` fork, used to re-build official docs using Read The Docs theme
  
* https://github.com/python-docs-101/python-docs-101.github.io

  * GitHub Pages website hosting the output of the fork of the official docs.


^^^^^^^^^^^^
Product
^^^^^^^^^^^^
| Official Docs with TOC Sidebar:
| https://python-docs-101/python-docs-101.github.io


|
|
|
|
|
| Original readme below this line
|
|
|
|
|

**************************
Read the Docs Sphinx Theme
**************************

.. image:: https://img.shields.io/pypi/v/sphinx_rtd_theme.svg
   :target: https://pypi.python.org/pypi/sphinx_rtd_theme
   :alt: Pypi Version
.. image:: https://circleci.com/gh/readthedocs/sphinx_rtd_theme.svg?style=svg
   :alt: Build Status
   :target: https://circleci.com/gh/readthedocs/sphinx_rtd_theme
.. image:: https://img.shields.io/pypi/l/sphinx_rtd_theme.svg
   :target: https://pypi.python.org/pypi/sphinx_rtd_theme/
   :alt: License
.. image:: https://readthedocs.org/projects/sphinx-rtd-theme/badge/?version=latest
  :target: http://sphinx-rtd-theme.readthedocs.io/en/latest/?badge=latest
  :alt: Documentation Status

This Sphinx_ theme was designed to provide a great reader experience for
documentation users on both desktop and mobile devices. This theme is used
primarily on `Read the Docs`_ but can work with any Sphinx project. You can find
a working demo of the theme in the `theme documentation`_

.. _Sphinx: http://www.sphinx-doc.org
.. _Read the Docs: http://www.readthedocs.org
.. _theme documentation: https://sphinx-rtd-theme.readthedocs.io/en/stable/

Installation
============

This theme is distributed on PyPI_ and can be installed with ``pip``:

.. code:: console

   $ pip install sphinx-rtd-theme

To use the theme in your Sphinx project, you will need to edit
your ``conf.py`` file's ``html_theme`` setting:

.. code:: python

    html_theme = "sphinx_rtd_theme"

.. admonition:: See also:

    `Supported browsers`_
        Officially supported and tested browser/operating system combinations

    `Supported dependencies`_
        Supported versions of Python, Sphinx, and other dependencies.

    `Example documentation`_
        A full example of this theme output, with localized strings enabled.

.. _PyPI: https://pypi.python.org/pypi/sphinx_rtd_theme
.. _Supported browsers: https://sphinx-rtd-theme.readthedocs.io/en/stable/development.html#supported-browsers
.. _Supported dependencies: https://sphinx-rtd-theme.readthedocs.io/en/stable/development.html#supported-dependencies
.. _Example documentation:  https://sphinx-rtd-theme.readthedocs.io/en/stable/

Configuration
=============

This theme is highly customizable on both the page level and on a global level.
To see all the possible configuration options, read the documentation on
`configuring the theme`_.

.. _configuring the theme: https://sphinx-rtd-theme.readthedocs.io/en/stable/configuring.html

Contributing
============

If you would like to help modify or translate the theme, you'll find more
information on contributing in our `contributing guide`_.

.. _contributing guide: https://sphinx-rtd-theme.readthedocs.io/en/stable/contributing.html
