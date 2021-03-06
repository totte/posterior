Overview
========

Acumen aims at providing a Python module capable of parsing Pacman packages
and PKGBUILDs as well as the repositories and databases designed to provide
them. Originally created as 'Parched' by Sebastian Nowicki, this fork is an
intent to continue the work and extend the provided functionality.

Installing
==========

Pip
---

acumen is not currently registered with `PyPI <http://pypi.python.org>`_ due to it's
development status, however pip can install the module from a git repository::

    pip install -e git://github.com/totte/acumen.git

Manual
------

First retrieve the source from the `git repository
<http://github.com/totte/acumen/>`_, then follow the typical install
procedure::

    git clone git://github.com/totte/acumen.git
    cd acumen
    python setup.py install


Documentation
=============

The documentation is not available online, however, you can retrieve the
source and generate the documentation using sphinx::

    git clone git://github.com/totte/acumen.git
    cd acumen/docs
    make html

The code itself is also documented, so you can simply look at acumen.py.


License
=======

Acumen is MIT licensed.
