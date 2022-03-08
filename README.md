Postgresql
=========

A role to deploy Postgresql in a Docker container.

Requirements
------------

- Docker

Role Variables
--------------

For all variables please see `defaults/main.yml`.

    generic_postgresql_database_user: "dummyuser"
    generic_postgresql_database_password: "dummypassword"
    
The credentials need to be set by your own.


Dependencies
------------

None

Example Playbook
----------------

    ---
    - hosts: all
      roles:
        - generic_postgresql_role