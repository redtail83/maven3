Ansible Role: Maven3
=========

Install Maven3 for CentOS and Ubuntu linux.

Requirements
------------

None.

Role Variables
--------------

Here is the list of all variables for this role.
```yml
# Base URL of Maven3 download site.
site_url: http://ftp.jaist.ac.jp/pub

# Maven version.
maven3_version: 3.6.0
```

Dependencies
------------

This role depends on:

* redtail83.oraclejdk8

Example Playbook
----------------

Both CentOS 7 and Ubuntu 16.04:

    - hosts: servers
      roles:
         - { role: redtail83.maven3 }

License
-------

MIT
