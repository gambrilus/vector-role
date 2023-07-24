Ansible role: vector-role
=========

Deploy & configure Vector on Centos 7 using ansible.

Requirements
------------

Ansible >= 2.7 (It might work on previous versions, but we cannot guarantee it)

Role Variables
--------------

| vars | description    | default value |
|------|----------------|---------------|
|vector_version   | vector version |0.31.0       |
|vector_config_dir   | work directory |/etc/vector               |


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - vector-role



License
-------

MIT

Author Information
------------------

Andrey Gavrilov, Netology Student
