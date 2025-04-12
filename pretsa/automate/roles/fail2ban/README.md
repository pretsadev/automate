Role Name
=========

pretsa.automate.fail2ban

Requirements
------------

N/A

Role Variables
--------------

- fail2ban_ssh_maxretry: ssh jail max retry (default to 3)
- fail2ban_ssh_findtime: ssh jail find time (default to 10w)
- fail2ban_ssh_bantime: ssh jail abn time (default to 10w)

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - pretsa.automate.fail2ban

License
-------

MIT

Author Information
------------------

[PRETSA](https://pretsa.dev)
