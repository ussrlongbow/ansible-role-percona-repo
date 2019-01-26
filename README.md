Role Name
=========

Ansible role to configure Percona Software repositories.
See https://www.percona.com/doc/percona-repo-config/index.html

Requirements
------------

Currently only Debian-based distributions are supported

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

As simple as:

    - hosts: servers
      roles:
         - role: ussrlongbow.percona-repo

License
-------

MIT

Author Information
------------------

Valentin Gostev (val@Le.lc)
