---
title: 'Role for virtualhost_role'
description: 'Quickstart and examples for demonstrating the role capabilities.'
---

# Ansible Role: Virtualhost_role

## Status

[![Build Status](https://travis-ci.org/lordoftheflies/virtualhost_role.svg?branch=master)](https://travis-ci.org/lordoftheflies/virtualhost_role)

## Description

Virtualhost_role is an Ansible role used to setup and maintain production grade services.

## Roadmap

* [ROADMAP.md](ROADMAP.md)

## References

* [docs.ansible.com](https://docs.ansible.com/)
* [On Ansible Galaxy](https://galaxy.ansible.com/lordoftheflies/virtualhost_role)

## Requirements

### Production

* Ansible

### For Local Testing

* [Vagrant](https://www.vagrantup.com/) - (Tested using version 2.1.1)
* Vagrant plugins:
  * [vagrant-disksize (0.1.2)](https://github.com/lordoftheflies/vagrant-disksize)
  * [vagrant-libvirt](https://github.com/lordoftheflies/vagrant-libvirt)
  * vai (0.9.3) - For testing with multiple vms [vagrant-plugin-vai](https://github.com/lordoftheflies/vagrant-plugin-vai)
  * [vagrant-vbguest (0.15.2) - Recommended vagrant-vbguest](https://github.com/lordoftheflies/vagrant-vbguest)
* [Virtual Box](https://www.virtualbox.org/)
  * Tested using Version 5.2.14 r123301 (Qt5.6.1)

## Variables

### defaults/main.yml

* [defaults/main.yml](defaults/main.yml) contains all of the required variables.

### project_name/site.yml example

* [example_virtualhost_role.yml](files/example_site.yml) may contain an example entry.

## Testing

To test with all VM's defined in Vagrantfile run the following:

```shell
cd roles/virtualhost_role
vagrant up
```

To run on a specific VM's
```shell
vagrant up xenial
```

### VM's tested with Vagrant and Virtualbox

pass, fail, untested, unsupported


| OS | Version | Distribution | Supported [^1](#) | Results  |
| :--- | :---: | :---: | :---: | :---: |


## Authors

- [lordoftheflies](mailto:lordoftheflies)

## License: [MIT](https://tldrlegal.com/license/mit-license)

* virtualhost_role generated using [ansible_collection_skeleton](https://github.com/lordoftheflies/ansible_collection_skeleton)