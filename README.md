vmbuilder-formula
=================

vmbuilder-formula
This formula create vm machine using vmbuilder.

install
=================
gitfs:
  - https://github.com/fessoga5/vmbuilder-formula.git

or copy vmbuilder dir in /srv/salt

You should copy _states in /srv/salt, because formula using my states, kvm.py

.. note::
    See the full `Salt Formulas installation and usage instructions
    <http://docs.saltstack.com/en/latest/topics/development/conventions/formulas.html>`_.

Available states
================

.. contents::
    :local:

``vmbuilder``
-------------

Installs the ``vmbuilder`` and package and service for libvirt.

``vmbuilder.machine``
---------------------

Create and confire virtual machine from pillar.


Support
================
Check in Ubuntu 14.04