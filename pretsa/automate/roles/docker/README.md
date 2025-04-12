Role Name
=========

pretsa.automate.docker

Requirements
------------

N/A

Role Variables
--------------

- docker_api_expose: Whether to expose docker API on TCP (default to false)
- docker_api_address: ATCP address to expose docker API on

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - pretsa.automate.docker

License
-------

MIT

Author Information
------------------

[PRETSA](https://pretsa.dev)
