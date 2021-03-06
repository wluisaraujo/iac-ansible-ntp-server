[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-NTP%20Server-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-ntp-server)[![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-ntp.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-ntp)

# IaC: with [Ansible](https://www.ansible.com) role to install and configure [NTP Server](www.ntp.org/)
------------

Description
------------

 * Ansible for NTP Server
 
Requirements
------------

 *

Installation
------------

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.ntp
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.ntp/requirements.txt
```

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - ntp
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)