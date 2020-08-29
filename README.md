Ansible Docker Role
=========

This role installs the current Edge build Docker CE using the official repo, for more information on Docker CE see the official site at [https://www.docker.com/community-edition](https://www.docker.com/community-edition).

Requirements
------------

Apart from requiring root access via 'become: yes' this role has no special requirments

Role Variables
--------------

All variables can be found in 'vars' folder.

Dependencies
------------

None.

Example Playbook
----------------
```
- hosts: docker
  gather_facts: true
  become: yes
  become_method: sudo
  
  roles:
    - raba-nk.docker
```

License
-------

BSD

Author Information
------------------

This role is publishe by [raba-nk]
