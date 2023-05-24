# ansible-apps_rt

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_rt-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_rt)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_rt.svg)](https://github.com/lotusnoir/ansible-apps_rt/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_rt?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_rt)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_rt)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_rt)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Install and configure Best Practical's Request Tracker (RT).

RT depends on many Perl modules, Apache with either mod_perl or mod_fcgid, and PostgreSQL or MySQL.
RT prefers mod_fcgid and MySQL.

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_rt
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_rt


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
