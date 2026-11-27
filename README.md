# ansible-nodejs

Setups NodeJS from nodesource APT packages

## Requirements

- `ansible-core` 2.19 or newer.

## Example playbook

```yaml
---
- hosts: myserver
  remote_user: root
  become: false
  roles:
    - role: sunfoxcz.nodejs
      node_version: 12
```

## Mandatory variables

None

## Optional variables

 * node_version

## Default values
```yaml
node_version: 12 # 10, 12, 13, 14 available
```

## License

Licensed under MIT license. See [LICENSE](LICENSE.md) for details.
