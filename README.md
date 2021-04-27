# jtprogru.install_atop

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-install-atop/CI?label=CI)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-install-atop/Release?label=Release)
![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-install-atop)
[![Ansible Role](https://img.shields.io/ansible/role/53346)](https://galaxy.ansible.com/jtprogru/hinstall_atop/)
[![GitHub tag](https://img.shields.io/github/tag/jtprogru/ansible-role-install-atop.svg)](https://github.com/jtprogru/ansible-role-install-atop/tags)

Simple role for install atop on remote server.


## Role Variables


See [`defaults/main.yml`](defaults/main.yml).


## Example Playbook

Example playbook:
```yaml
---
- name: Installing atop
  hosts: all
  become: true

  roles:
    - jtprogru.install_atop
```

## License

See [LICENSE](LICENSE.md)
