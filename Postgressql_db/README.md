Role Name
=========

Postgressql database creation

Requirements
------------

Package Needed

1) Python
2) Pip3

Role Variables
--------------

Variables are added in defaults directory

1) db_name: 'postgress_db'
2) user_name: 'thinknyx'
3) password: 'Thinknyx@07'
4) schema_name: 'thinknyx_schema'


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too
```
---
 - name: Executing a Role
   hosts: <<Group/Hostname>>
   tasks:
     - name: include role
       include_role:
         name: Postgressql_db
```
License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
