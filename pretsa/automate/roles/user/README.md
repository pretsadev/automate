Role Name
=========

pretsa.automate.user

Requirements
------------

N/A

Role Variables
--------------

- users: arrays of user with these sub-variables
  - user_name: Name of user
  - user_password: Encoded password
  - user_shell: User shell (defaults to /bin/bash)
  - user_groups: User groups (defaults to users)
  - user_public_keys: arrays of URL for public keys that can SSH as this user

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - pretsa.automate.user

License
-------

MIT

Author Information
------------------

[PRETSA](https://pretsa.dev)
