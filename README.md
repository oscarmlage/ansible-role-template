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
  src: git://git@git.oscarmlage.com/ansible/ansible-role-template.git
  scm: git
```
* playbook.yml
```yaml
- hosts: all
  roles:
    - ansible-role-template
```

## License

MIT / BSD

