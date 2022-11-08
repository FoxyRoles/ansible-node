# ansible-nodejs

Setups NodeJS from nodesource APT packages

## Example playbook

```yaml
---
- hosts: myserver
  user: root
  sudo: False
  roles:
   - sunfoxcz.nodejs
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
