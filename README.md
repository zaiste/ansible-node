ansible-node
=========

Ansible role that installs Node for Ubuntu Xenial from the NodeSource APT.

Requirements
------------

None.

Role Variables
--------------

- `version` defaults to `8.x`
- `dist` defaults to `artful`

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: zaiste.node }

License
-------

MIT / BSD

Author Information
------------------

[Zaiste](http://zaiste.net) 2017
