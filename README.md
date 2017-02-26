openHAB
=========

Installs and configures an [openHAB](http://docs.openhab.org/index.html) home automation hub.

Requirements
------------

None.

Role Variables
--------------

`See [defaults/main.yml](defaults/main.yml)`.

Dependencies
------------

[mrlesmithjr.oracle-java8](https://galaxy.ansible.com/mrlesmithjr/oracle-java8/)

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: robgmills.openhab }

License
-------

MIT

Author Information
------------------

Written by [Rob Mills](https://robgmills.com).
