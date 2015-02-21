Elixir
========

An ansible role that install elixir.

Requirements
------------

Tested on Ansible 1.8.2 or higher.

Role Variables
--------------

- erlang_version: install erlang version
- elixir_version: installl elixir version

Dependencies
------------

none

Example Playbook
----------------

- hosts: servers
  sudo: yes
  roles:
     - { role: ohr486.ansible-elixir, erlang_version: 17.4, elixir_version: v1.0.3 }

License
-------

BSD

Author Information
------------------

ohr486

