# install_helm

Role to install [Helm](https://helm.sh/).

## Requirements

None.

## Role Variables

`install_helm_version` - Version of helm to install (Default: v3.14.0)

## Dependencies

None.

## Example Playbook

```yaml
- hosts: servers
      roles:
         - { role: wittdennis.install_helm, install_helm_version: v3.14.0 }
```

## License

MIT
