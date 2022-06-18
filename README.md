ansible-role-coturn
-------------------
This role was adapted from [systemli/coturn](https://github.com/systemli/ansible-role-coturn)

Install coturn for Nextcloud like described here:
https://help.nextcloud.com/t/howto-setup-nextcloud-talk-with-turn-server/30794


Role Variables
--------------

### Required Variables

The following variables are required (no defaults provided) and must always be
defined when using the role:

* `coturn_static_auth_secret`: Shared secret for client authentication. One way
  to generate an appropriate value is by using `pwgen -s 64 1`.
* `coturn_realm`: Use a syntactically correct hostname or domain.

### Optional Variables

See [defaults/main.yml](defaults/main.yml) for a list of optional variables.


Supported OS
------------
- Ubuntu 20.04
- Debian 10
- Debian 11
- Fedora 35


License
-------

GPLv3
