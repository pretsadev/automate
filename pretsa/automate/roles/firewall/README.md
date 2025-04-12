Role Name
=========

pretsa.automate.firewall

Requirements
------------

N/A

Role Variables
--------------

- firewall_allow_networks: Netowrks to allow (default to empty)
- firewall_allow_ports: Ports to allow (defaults to empty)

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - pretsa.automate.firewall

License
-------

MIT

Author Information
------------------

[PRETSA](https://pretsa.dev)
