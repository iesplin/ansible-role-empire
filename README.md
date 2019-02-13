ansible-role-empire
=========

Ansible role for installing Empire Project in Kali

Dependencies
------------

ansible-role-powershell

Role Variables
--------------

empire_dir: /opt/Empire

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: ansible-role-empire

License
-------

MIT