ansible-role-jetbrains-mono
=========

This role installs the JetBrains Mono font onto an Ubuntu system.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here.

- `unzip` apt packages for the `unarchive` Ansible module

```bash
sudo apt-get install -y unzip
```

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

```yaml
---
jetbrains_mono_version: 1.0.3
jetbrains_mono_url: "https://download.jetbrains.com/fonts/JetBrainsMono"
```

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: servers
      roles:
         - { role: iancleary.jetbrains_mono }
```

License
-------

[MIT](LICENSE)

Author Information
------------------

This role was created in 2020 by [Ian Cleary](https://iancleary.me).

Inspiration for the structure of this repo came from [Jeff Geerling](https://github.com/geerlingguy/ansible-role-nginx).
