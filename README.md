andrewrothstein.porter
=========
![Build Status](https://github.com/andrewrothstein/ansible-porter/actions/workflows/build.yml/badge.svg)

Installs [Porter](https://porter.sh). Does not support named versions. PRs accepted.

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
    - andrewrothstein.porter
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
