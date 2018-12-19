
Entrapment
=========

An Ansible role that installs the Palo Alto Networks Traps agent on Linux hosts

Requirements
------------
The Traps installer for the Linux platform should be downloaded from the Traps Management Service (TMS) and placed in a `files/` directory where the playbook is located.

Role Variables
--------------
Available variables are listed below, along with default values (see defaults/main.yml):
```
linux_installer: filename
```

Usage
-----
For details on how to deploy the Traps agent to Linux hosts in the cloud, please refer to the ([wiki](https://github.com/stealthllama/ansible-role-entrapment/wiki)).

Dependencies
------------
None

Example Playbook
----------------
```
---
- name: install traps
  hosts: all
  become: yes

  roles:
  - stealthllama.entrapment
```

License
-------

Apache 2.0

Author Information
------------------

Role created by Robert Hagen ([@stealthllama](https://github.com/stealthllama)).
