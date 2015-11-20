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
- elixir_version: elixir version (v1.1.1, v1.1.0, v1.0.5, ...)
- erlang_version: erlang version (18.1, 18.0, 17.5, ...)
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
     - { role: ohr486.elixir, erlang_version: 18.1, elixir_version: v1.1.1, erl_configure_options: '--enable-hipe --enable-smp-support' }
```

License
-------

MIT

Author Information
------------------

ohr486

