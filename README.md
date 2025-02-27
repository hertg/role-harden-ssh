# hertg.harden_ssh

Ansible Galaxy role to harden SSH server configuration on Debian.

## Installation

```
ansible-galaxy role install hertg.harden_ssh
```


## Usage

```yml
- name: Enable security updates
  include_role:
    name: hertg.harden_ssh
  vars:
    disable_root: true # default
    allow_local_root: false # default
    sshd_config: /etc/ssh/sshd_config # default
```
