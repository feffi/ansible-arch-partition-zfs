# ansible-arch-partition-zfs

Ansible role to manage a zfs "partition".

[![Build Status](https://img.shields.io/travis/feffi/ansible-arch-partition-zfs.svg)](https://travis-ci.org/feffi/ansible-arch-partition-zfs) [![Github All Releases](https://img.shields.io/github/downloads/feffi/ansible-arch-partition-zfs/total.svg)](https://github.com/feffi/ansible-arch-partition-zfs) [![GitHub forks](https://img.shields.io/github/forks/feffi/ansible-arch-partition-zfs.svg?style=social&label=Fork)](https://github.com/feffi/ansible-arch-partition-zfs) [![GitHub stars](https://img.shields.io/github/stars/feffi/ansible-arch-partition-zfs.svg?style=social&label=Star)](https://github.com/feffi/ansible-arch-partition-zfs) [![GitHub watchers](https://img.shields.io/github/watchers/feffi/ansible-arch-partition-zfs.svg?style=social&label=Watch)](https://github.com/feffi/ansible-arch-partition-zfs) [![Twitter Follow](https://img.shields.io/twitter/follow/feffi1.svg?style=social&label=Follow)](https://twitter.com/feffi1) [![License](http://img.shields.io/:license-mit-blue.svg)](https://github.com/feffi/ansible-arch-partition-zfs/blob/master/LICENSE)

## Requirements

- Ansible 2.7.1
- pacman ;-)

### ansible.cfg

```yaml
hash_behaviour = merge
```

## Install

Just add the role to your ``requirements.yml`` file:

```yaml
- src: https://github.com/feffi/ansible-arch-partition-zfs.git
  name: ansible-arch-partition-zfs
```

## Role Defaults Variables

```yaml
ansible_arch_partition_zfs: {
}
```

Example:

```yaml
- hosts: all
  vars:
    ansible_arch_partition_zfs:
  roles:
    - { role: ansible-arch-partition-zfs }
```
