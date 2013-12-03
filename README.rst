Overview
========

Posterior aims at providing a Python module capable of parsing Pacman packages
and PKGBUILDs as well as the repositories and databases designed to provide
them. Originally created as 'Parched' by Sebastian Nowicki, this fork is an
intent to continue the work and extend the provided functionality.

Installing
==========

Pip
---

Posterior is not currently registered with `PyPI <http://pypi.python.org>`_ due to it's
development status, however pip can install the module from a git repository::

    pip install -e git://github.com/totte/posterior.git

Manual
------

First retrieve the source from the `git repository
<http://github.com/totte/posterior/>`_, then follow the typical install
procedure::

    git clone git://github.com/totte/posterior.git
    cd posterior
    python setup.py install


Documentation
=============

The documentation is not available online, however, you can retrieve the
source and generate the documentation using sphinx::

    git clone git://github.com/totte/posterior.git
    cd posterior/docs
    make html

The code itself is also documented, so you can simply look at posterior.py.


License
=======

Posterior is MIT licensed.
