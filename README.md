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
| netbird.skip_login | Skip Login step, useful for testing       | False                       |

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: servers
  roles:
  - crimsonfez.netbird
  vars:
    netbird:
      mgmt_url: https://netbird.example.com
      setup_key: "1234567890"

License
---

MIT

Author Information
------------------

David Kovari
