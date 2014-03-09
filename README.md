Virtualenv [![Build Status](https://travis-ci.org/brad/ansible-virtualenv.png?branch=master)](https://travis-ci.org/brad/ansible-virtualenv)
==========

Ansible role to install virtualenv, for distributions that don't have a pip package

Requirements
------------

Python 2.6+

Role Variables
--------------

* virtualenv_version: This variable can be set to any version found on [PyPi](https://pypi.python.org/pypi/virtualenv). Default is 1.11.4.
* virtualenv_path: The path prefix to install virtualenv in. The default is "/usr/local"

License
-------

GPLv3
