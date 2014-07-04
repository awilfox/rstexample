.. include:: <isonum.txt>

Mason
=====

Introduction
------------
This is mason, a system for managing, deploying, and maintaining one or more
groups of physical computers.

Quick start
-----------

::

  pip install git@github.com:Centarra/mason
  vi /etc/mason.conf
  service mason start

Note that this is subject to change.

Providers
---------
mason supports a concept known as *data providers*.  This allows backends to be
changed and configured easily.  Currently only SQL is supported.  In the future
this may be expanded to XML, JSON, etc.

Development / Testing
---------------------
You will most likely need a virtual machine host and/or private VLAN.  Some VM
solutions provide "fake" IPMI, which could be used to develop and test IPMI
functionality as well.

License
-------
This software is Copyright |copy| 2014 Centarra Networks Inc.  
