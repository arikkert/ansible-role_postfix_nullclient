Role Name
=========

Installs and configures postfix as nullclient on Linux host


Requirements
------------

deploy host has *ansible* and *ansible-galaxy* installed.  
Root access to target host

Role Variables
--------------

*email_root* set in inventory. Defaults to *root*

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: podman01
      roles:
         - arikkert.postfix_nullclient

Example of script that uses this role : https://github.com/arikkert/ansible-podman

License
-------

BSD

Author Information
------------------

    ARK-ICT
    Andre Rikkert de Koe - ICT
