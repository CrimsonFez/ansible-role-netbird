crimsonfez.netbird
=========

Install Netbird and login with a setup key.

Requirements
------------

Debian 12 or later

Role Variables
--------------


| Name               | Description                               | Default Value               |
| -------------------- | ------------------------------------------- | :---------------------------- |
| netbird.mgmt_url   | Management Server                         | https://app.netbird.io:443/ |
| netbird.setup_key  | Setup Key used when registering the agent | ""                          |
| netbird.skip_login | Skip Login setup                          | False                       |

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: servers
  roles:
  - { role: username.rolename, x: 42 }
    License

---

MIT

Author Information
------------------

David Kovari
