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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
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
