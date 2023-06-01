Role Name
=========

Install Redis exporter from this [repo](https://github.com/oliver006/redis_exporter/releases)

Default installed version is v1.50.0

Requirements
------------

SystemD Installed 

Role Variables
--------------

All vars is available in [defaults/main.yml](defaults/main.yml)

Dependencies
------------

Think to install redis on your server

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: msterhuj.redis_exporter, redis_exporter_version: v1.50.0 }

License
-------

MIT

Author Information
------------------

MsterHuj
