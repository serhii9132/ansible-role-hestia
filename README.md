ansible-role-hestia
===================

A role for the basic configuration of Hestia CP.

Supported platfroms:
```
- Debian 12 (Bookworm)
- Ubuntu 22.04 (Jammy Jellyfish)
- Ubuntu 24.04 (Noble Numbat)
```

Requirements
------------

This role requires Ansible 2.19 or higher

Role Variables
--------------

The role variables and their descriptions can be found [here](https://github.com/serhii9132/ansible-role-hestia/blob/main/defaults/main.yaml).

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - serhii9132.ansible-role-hestia
```

License
-------

MIT