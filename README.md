# Ansible Role: Percona software stack


Installs the [Percona](https://percona.com) software stack on RHEL/CentOS.

## Requirements

Needs EPEL repository, pulls geerlingguy.repo-epel as a requirement.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    percona_add_repo: true
    percona_xtrabackup_version: 24
    percona_install_xtrabackup: true


## Dependencies

geerlingguy.repo-epel

## Example Playbook

    - hosts: percona
      roles:
        - wildy.percona

## License

MIT / BSD

## Author Information

This role was created in 2016 by Yuri Gorshkov.
