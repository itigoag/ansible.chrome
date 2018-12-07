# Ansible Role: chrome

[![Build Status](https://img.shields.io/travis-ci/itigoag/ansible.chrome.svg?branch=master&style=popout-square)](https://travis-ci.org/itigoag/ansible.chrome) [![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=popout-square)](licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-chrome-blue.svg?style=popout-square)](https://galaxy.ansible.com/itigoag/chrome) [![Ansible Role](https://img.shields.io/ansible/role/d/34928.svg?style=popout-square)](https://galaxy.ansible.com/itigoag/chrome)

## Description

Installs then Chrome on Windows devices and configures Chrome with Policy.

## Installation

```bash
ansible-galaxy install itigoag.chrome
```

## Requirements

none

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| chrome_install | true | Firefox installed or not installed |
| chrome_policies | | Standart Policies |
| chrome_policies_group | | Group Policies |
| chrome_policies_host | | Host Policies |

## Dependencies

none

## Example Playbook

```yml
- hosts: all
  roles:
     - itigoag.chrome
```

## Changelog

### 1.0.0

* inital commit

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)
* [ITIGO AG](https://www.itigo.ch)

## License

This project is under the MIT License. See the [LICENSE](licence) file for the full license text.

## Copyright

(c) 2018, Simon Bärlocher
(c) 2018, ITIGO AG