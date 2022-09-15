# Ansible Role: Template

## Requirements

None.

## Role Variables

None.

## Use with Ansible

* `ansible.cfg`:
```
[defaults]
roles_path = roles/
```
* Install role via galaxy: `ansible-galaxy install -r requirements.yml`
* `requirements.yml`:
```yaml
- name: ansible-role-template
  src: ssh://git@git.oscarmlage.com:10022/ansible/ansible-role-template.git
  scm: git
  version: main
```
* `playbook.yml`
```yaml
- hosts: all
  roles:
    - ansible-role-template
```

## License

MIT / BSD

