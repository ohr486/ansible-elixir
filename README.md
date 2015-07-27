Elixir
========

An ansible role that install elixir.

Requirements
------------

Tested on Ansible 1.8.2 or higher.

sudo to run.

Role Variables
--------------

```
- elixir_version: elixir version (v1.0.5, v1.0.4, v1.0.3, v1.0.2, v1.0.1, v1.0.0)
- erlang_version: erlang version (17.5, 17.4, 17.3, ...)
```

Dependencies
------------

none

Example Playbook
----------------

```
- hosts: servers
  sudo: yes
  roles:
     - { role: ohr486.elixir, erlang_version: 17.5, elixir_version: v1.0.5 }
```

License
-------

MIT

Author Information
------------------

ohr486

