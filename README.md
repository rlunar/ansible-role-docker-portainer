# Ansible Role - Portainer for Docker
[![Build Status](https://travis-ci.org/rlunar/ansible-role-docker-portainer.svg?branch=master)](https://travis-ci.org/rlunar/ansible-role-docker-portainer)

## Requirements
This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Role Variables
- [`defaults/main.yml`](https://github.com/rlunar/ansible-role-docker-portainer/blob/master/defaults/main.yml)

## Example Playbook
```
- hosts: localhost
  roles:
    - role: rlunar.docker-portainer
```

## Dependencies
- `docker` should be installed and working (you can use the `mongrelion.docker` role to install).

##  License
MIT

##  Author Information
This role was created in 2017 by [Roberto Luna](https://github.com/rlunar/) original package created by [elnebuloso](https://github.com/elnebuloso/)
