# Ansible Role: nodejs

JavaScript runtime built on Chrome's V8 JavaScript engine.

[https://nodejs.org](https://nodejs.org)

# Role Variables

```
nodejs_version: 8.12
```

Version of nodejs to install.

```
install_buildtools: no
```

Install build tools or not.(build-essential in debain or gcc-c++ and make in RedHat).

# Example Playbook

```
- hosts: server
  vars:
    nodejs_version: 8.12
    install_buildtools: yes
  roles:
    - { role: honomoa.nodejs }
```

# License
CC BY-SA 3.0
