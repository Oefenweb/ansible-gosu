## gosu

[![CI](https://github.com/Oefenweb/ansible-gosu/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-gosu/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-gosu-blue.svg)](https://galaxy.ansible.com/Oefenweb/gosu/)

Set up (the latest or a specific version of) [gosu](https://github.com/tianon/gosu) in Debian-like systems.

#### Requirements

None

#### Variables

* `gosu_version` [default: `1.12`]: Version to install
* `gosu_install_prefix` [default: `/usr/local/bin`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.gosu
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-gosu/issues)!
