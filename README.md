andrewrothstein.nss-pam-ldap-supervisord
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-nss-pam-ldap-supervisord.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-nss-pam-ldap-supervisord)

Launches the processes need for nss-pam-ldap to work

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
    - andrewrothstein.nss-pam-ldap-supervisord
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
