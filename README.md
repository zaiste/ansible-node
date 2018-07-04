# ansible-node

Ansible role that installs Node for Ubuntu 18.04 (Bionic Beaver) using the NodeSource APT.

## Requirements

None.

## Role Variables

- `version` defaults to `10.x`
- `dist` defaults to `bionic`

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

[Zaiste](http://zaiste.net) 2018
