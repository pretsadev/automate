Role Name
=========

pretsa.automate.package

Requirements
------------

N/A

Role Variables
--------------

- package_id: Packages installation id
- package_add_repo: Packages to install require adding a repo (default  to false)
- package_apt_gpg_key_url: URL of GPG key of repo to be added (APT) 
- package_apt_repo_url: URL of repo to be added (APT)
- package_yum_gpg_key_url: URL of GPG key of repo to be added (YUM)
- package_yum_repo_url: URL of repo to be added (YUM)
- package_yum_prerequisite: Pre-requisite packages to install (APT)
- package_apt_prerequisite: Pre-requisite packages to install (YUM)
- package_name: Packages to install

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - pretsa.automate.package

License
-------

MIT

Author Information
------------------

[PRETSA](https://pretsa.dev)
