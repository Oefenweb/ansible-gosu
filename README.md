## gosu

[![Build Status](https://travis-ci.org/Oefenweb/ansible-gosu.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-gosu) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-gosu-blue.svg)](https://galaxy.ansible.com/Oefenweb/gosu/)

Set up (the latest or a specific version of) [gosu](https://github.com/tianon/gosu) in Debian-like systems.

#### Requirements

None

#### Variables

* `gosu_version` [default: `1.10`]: Version to install
* `gosu_install_prefix` [default: `/usr/local/bin`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - gosu
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-gosu/issues)!
