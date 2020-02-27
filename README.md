Ansible role for jasper
==================================

Installs the Jasper service

[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-jasper/workflows/Molecule%20Test/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-jasper/actions?query=workflow%3A%22Molecule+Test%22)
[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-jasper/workflows/Release/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-jasper/actions?query=workflow%3A%22Release%22)

Requirements
------------

None

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-------:|:--------:|
| `jasper_curator_url` | Specify which curator binary url you want to download from | string | "" | no

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: ansible-role-jasper
```

License
-------

[Apache License](LICENSE)
