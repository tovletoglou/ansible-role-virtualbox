# Ansible Role: Oracle VirtualBox

Install and configure Terminator terminal: <https://www.virtualbox.org/>

## Requirements

- Ansible >= 2.2
- Fedora 25
- sudo

The role may run on other systems, but it is not tested.

## Role Variables

The default version to install.

```
virtualbox_version: VirtualBox-5.1
```

Keep update with minor versions 5.1.x (present | latest | absent).

```
virtualbox_update: latest
```

## Example

```
- hosts: all
  roles:
    - ansible-role-virtualbox
```

## Dependencies

None

## License

MIT

## Author Information

Apostolos Tovletoglou [ansible-role-virtualbox](https://github.com/tovletoglou/ansible-role-virtualbox)
