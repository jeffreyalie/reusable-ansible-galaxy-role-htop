# htop

Ansible role to install `htop` on Ubuntu systems.

## Requirements

None. Uses only `ansible.builtin` modules.

## Role Variables

| Variable | Default | Description |
|---|---|---|
| `htop_package` | `htop` | Package name to install |
| `htop_state` | `present` | `present` to install, `absent` to remove |

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  become: true
  roles:
    - role: jeffrey.htop
```

## License

MIT

## Author

jeffrey
