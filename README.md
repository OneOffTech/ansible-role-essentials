Essentials
=========

Debian installer for essential software packages.

This is work in progress and it is prefered to collaborate on it. Please communicate over the issue queue. Every pull request is highly appreciated.

Requirements
------------

None


Role Variables
--------------

```yaml
essential_packets:
  - apt-transport-https
  - ca-certificates
  - curl
  - dnsutils
  - geoip-bin
  - git
  - htop
  - iftop
  - iotop
  - locate
  - nano
  - ncdu
  - net-tools
  - python-pip
  - python3
  - python3-pip
  - rsync
  - screen
  - sed
  - sudo
  - tmux
  - tree
  - vim-nox
  - wget
  - whois
  - zsh
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: xamanu.essentials }

License
-------

MIT

Author Information
------------------

Felix Delattre - https://felix.delattre.de
