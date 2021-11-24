redhat-ha
=========

Ansible role to upgrade OS rhel{7,8}

Requirements
------------

The following collections must be installed:

```
$ ansible-galaxy collection install ansible.posix -p collections
$ ansible-galaxy collection install community.general -p collections
```

Role Variables
--------------

ToDo

Dependencies
------------

ToDo

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }



$ ansible-playbook -i inventory playbook.yml --tags prerequisites,os-update-and-upgrade-rhel -e '{filesystem_threshold: 65}'

License
-------

BSD

Author Information
------------------

silvinux
