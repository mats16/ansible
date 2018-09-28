# softether

ansible role for [softether](https://www.softether.org/)

## Requirements

- systemd

## Role Variables

```yml
softether_version: "v4.25-9656-rtm-2018.01.15"
```

## Dependencies

none

## Example Playbook

```yaml
- hosts: vpn-server
  roles:
    - role: softether
```
