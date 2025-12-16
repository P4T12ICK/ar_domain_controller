# Ansible Role: [Attack Range](https://github.com/splunk/attack_range) Domain Controller

An Ansible Role that installs a [Attack Range](https://github.com/splunk/attack_range) Windows Server Domain Controller.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):
```
ar_domain_controller_password: Pl3ase-k1Ll-me:p
```

## Dependencies

None.

## Example Playbook

```yaml
- hosts: attack_range_windows
  roles:
    - P4T12ICK.ar_domain_controller
```

## License
Apache License 2.0

## Author Information
This role was created by [P4T12ICK](https://github.com/P4T12ICK).
