# Ansible Role: Rolename

## Requirements

None.

## Role Variables

None.

## Use with Ansible

* Install this collection via gallaxy: `ansible-galaxy collection install -r collections/requirements.yml`
* Create a `playbook` with the following task:
```yaml
- name: 'Install rolename'
  hosts: all
  roles:
    - role: oscarmlage.rta_collection.rolename
      vars: {}
```

## License

MIT / BSD

