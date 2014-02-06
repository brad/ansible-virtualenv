Virtualenv
==========

Ansible role to install virtualenv, for distributions that don't have a pip package

Requirements
------------

Python 2.6+

Role Variables
--------------

* virtualenv_version: This variable can be set to any version found on [PyPi](https://pypi.python.org/pypi/virtualenv). Default is 1.11.2.
* virtualenv_path: The path prefix to install virtualenv in. The default is "/usr/local"

License
-------

GPLv3
