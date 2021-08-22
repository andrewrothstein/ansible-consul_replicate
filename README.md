andrewrothstein.consul_replicate
=========
![Build Status](https://github.com/andrewrothstein/ansible-consul_replicate/actions/workflows/build.yml/badge.svg)

Installs [consul-replicate](https://github.com/hashicorp/consul-replicate).

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.consul_replicate
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
