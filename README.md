generic admins
=========

# [![Build Status](https://travis-ci.org/ANTS-Framework/generic_admins.svg?branch=master)](https://travis-ci.org/ANTS-Framework/generic_admins)

Add an admin group to `/etc/sudoers`

Role Variables
--------------


```yml
    generic_admins__groupname: plz-change-me
```

Example Playbook
----------------


```yml
    - hosts: all
      vars:
        - generic_admins__groupname: your_admin_group
      roles:
         - generic_admins
```

License
-------

GPLv3

Author Information
------------------
Part of the [ANTS Framework](https://ants-framework.github.io/)
