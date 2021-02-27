# jtprogru.install_atop

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-install-atop/CI?label=CI) ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-install-atop/Release?label=Release) ![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-install-atop)

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
