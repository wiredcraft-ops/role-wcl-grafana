## Ansible-Grafana
> an ansible role to install, configure and manage Grafana

### Installation

```
# requirements.yml
- src: https://github.com/wiredcraft-ops/role-wcl-grafana.git
  name: wcl-grafana
  version: master
```

```bash
ansible-galaxy install -r requirements.yml -p roles
```


### Example Playbook

```yaml
- hosts: server
  roles:
    - role: wcl-grafana
```
