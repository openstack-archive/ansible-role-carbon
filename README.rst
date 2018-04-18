===================
ansible-role-carbon
===================

Ansible role to manage graphite-project/carbon

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-carbon.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-carbon
* Bugs: https://bugs.launchpad.net/ansible-role-carbon

Description
-----------

Carbon is one of the components of Graphite, and is responsible for receiving
metrics over the network and writing them down to disk using a storage
backend.

Requirements
------------

See `bindep.txt` for role dependencies.

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install carbon
      hosts: graphite
      roles:
        - ansible-role-carbon
