Ansible Role Jenkins
===============================================

Ansible role to install and configure jenkins on gentoo instances.

Supported Distributions
-----------------------

- Gentoo

Requirements
------------

Java has to be installed on target system. You can use this ansible role.
[vundb/ansible-role-java](https://github.com/vundb/ansible-role-java)

Role Variables
--------------

None.

Dependencies
------------

[vundb/ansible-role-portage](https://github.com/vundb/ansible-role-portage)

Example Playbook
----------------
```
- hosts: all
  roles:
    - role: vundb-jenkins
```

License
-------

MIT

Author Information
------------------

- You can find more roles in my GitHub channel [vundb](https://github.com/vundb)
- Follow me on Twitter [@vundb](https://twitter.com/vundb)
