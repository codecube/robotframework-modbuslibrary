ModbusLibrary for Robot Framework
=================================

Introduction
------------

ModbusLibrary is a `Robot Framework <http://robotframework.org>`__ test
library for testing Modbus.

The library has the following main usages:

- Reading and writing registers over serial line
- Reading and writing registers over socket

This is a very basic library which only handles a single connection.
Multiple connections will be implemented later.

ModbusLibrary is open source software licensed under `Apache License 2.0
<http://www.apache.org/licenses/LICENSE-2.0.html>`__.

Installation
------------

When installing ModbusLibrary on UNIX-like machines with Python, the easiest
approach is using `pip <http://pip-installer.org>`__::

    pip install robotframework-modbuslibrary

Alternatively you can download the source distribution from `PyPI
<https://pypi.python.org/pypi/robotframework-modbuslibrary>`__, extract
it, and install it::

    python setup.py install

Documentation
-------------

Keyword documentation can be built running::

    make doc

For general information about using test libraries with Robot Framework, see
`Robot Framework User Guide`__.

__ http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#using-test-libraries
