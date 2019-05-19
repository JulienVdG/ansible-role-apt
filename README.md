ansible-role-apt
================

Setup APT with auto updates

Role Variables
--------------

`apt_auto_update`: default to true, setup unattended-upgrades with automatic 
                   call via /etc/apt/apt.conf.d/02periodic
		   as described in https://wiki.debian.org/UnattendedUpgrades

Dependencies
------------

n/a

Example Playbook
----------------

```
- hosts: hosts
  become: yes
  roles:
    - { role: ansible-role-apt }
```

License
-------

Copyright 2018-2019 Julien Viard de Galbert

Licensed under the Apache License, Version 2.0 (the "License"); you may
not use this file except in compliance with the License. You may obtain
a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations
under the License.

Author Information
------------------

Julien Viard de Galbert

http://silicone.blogsite.org/

