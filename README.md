Ansible-users
=========

Add users and groups to Linux host.

Requirements
------------

None

Role Variables
--------------

role variable:  
group: which group and members to create, defaults to ops.

defaults/main.yml:  
user_groups:  a list of the groups to create and the users in these groups.
The group name specified by the 'group' variable should be in this list.

Dependencies
------------

None

Example Playbook
----------------

An example playbook to test this role.

    - hosts: servers
      roles:
         - { role: ansible-users }

License
-------

BSD

Author Information
------------------

Abubakr-Sadik Nii Nai Davis  
https://github.com/ttousai  
@ttousai  
