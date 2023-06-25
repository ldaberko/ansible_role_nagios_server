Role Name
=========

Set up a nagios monitoring server.

Requirements
------------

msmtp and Apache should be installed.

Role Variables
--------------


Dependencies
------------

ldaberko/ansible_role_msmtp_relay
ldaberko/ansible_role_apache2_server

Example Playbook
----------------

    - hosts: servers
      roles:
         - nagios_server

License
-------

GPLv3
