# Ansible Playbook: Using ACI with MSO and VMM domains

## Ansible with ACI and MSO with VMM domains

This Ansible playbook consists of multiple plays of ACI, MSO, and vCenter.

## Requirements

This playbook requires the standard set of ACI and MSO modules from Ansible v2.7.

## Installation

Installing Ansible to run your playbooks:

There are two ways you can test this role:

1. Installing it by cloning the Github repository
```
git clone https://github.com/ansible/ansible.git
```
2. Install it using the ansible-galaxy command
```
https://docs.ansible.com/ansible/devel/installation_guide/intro_installation.html#running-from-source
```
## Using the mso.yml playbook

## Notes

- Over time when more ACI and MSO modules are released with Ansible, we will swap the aci_rest calls with the high-level module calls.
- Feel free to add additional functionality or report bugs and share it with us on Github https://github.com/ansible/ansible!

## License

Apache License 2.0
