Postgresql
=========

A role to deploy Postgresql in a Docker container.

Requirements
------------

- Docker

Role Variables
--------------

For all variables please see `defaults/main.yml`.

    generic_postgresql_container_env:
      POSTGRES_USER: admin
      POSTGRES_PASSWORD: password
Set credentials as environment variables


Dependencies
------------

None

Example Playbook
----------------

    ---
    - hosts: all
      roles:
        - generic_postgresql_role