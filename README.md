# Ansible Role: Oracle VirtualBox

Install Oracle VirtualBox <https://www.virtualbox.org/> from Oracle repository.

## Requirements

- Ansible >= 2.2
- Fedora 25
- sudo

The role may run on other systems, but it is not tested.

## Role Variables

The default version to install.

```yml
virtualbox_version: VirtualBox-5.1
```

Keep update with minor versions 5.1.x (`present | latest | absent`).

```yml
virtualbox_update: latest
```

## Example

```yml
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
