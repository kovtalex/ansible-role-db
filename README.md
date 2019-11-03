ansible-role-db
=========

[![Build Status](https://travis-ci.com/kovtalex/ansible-role-db.svg?branch=master)](https://travis-ci.com/kovtalex/ansible-role-db)

Requirements
------------

None

Installation
------------

```
- name: db
  src: https://github.com/kovtalex/ansible-role-db
```

Role Variables
--------------

Will be added

Dependencies
------------

None

Example Playbook
----------------

```
- hosts: db
  roles:
    - { role: db, mongo_bind_ip: 0.0.0.0 }
```

License
-------

BSD

Author Information
------------------

Alexey Kovtunovich