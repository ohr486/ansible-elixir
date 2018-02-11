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
- elixir_version: elixir version (v1.6.1, ...)
- erlang_version: erlang version (20.2, ...)
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
     - { role: ohr486.elixir, erlang_version: 20.2, elixir_version: v1.6.2, erl_configure_options: '--enable-hipe --enable-smp-support' }
```

License
-------

MIT

Author Information
------------------

ohr486

