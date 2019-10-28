andrewrothstein.porter
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-porter.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-porter)

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
