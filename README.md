# Ansible Remnux Role

[![CI](https://github.com/gr4unch3r/ansible-role-remnux/actions/workflows/ci.yml/badge.svg)](https://github.com/gr4unch3r/ansible-role-remnux/actions/workflows/ci.yml)

Ansible role to install [Remnux](https://remnux.org/) malware analysis toolkit.

## Requirements

- Ubuntu 20.04 LTS VM (e.g. [gr4unch3r/ubuntu-focal](https://app.vagrantup.com/gr4unch3r/boxes/ubuntu-focal))

## Example Playbook

```
- hosts: all
  become: true
  roles:
    - gr4unch3r.remnux
```

## License

MIT

## Author Information

gr4unch3r [at] protonmail [dot] com
