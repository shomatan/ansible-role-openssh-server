# Ansible role: ssh
Configures ssh service.

## Requirements
None.

## Supported Platforms
+ EL 6
+ EL 7

## Role Variables
|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|ssh_Port|Integer||22|
|ssh_PermitRootLogin|String||"no"|
|ssh_PubkeyAuthentication|String||"yes"|
|ssh_PermitEmptyPasswords|String||"no"|
|ssh_PasswordAuthentication|String||"no"|

## Dependencies
None.

## Example playbook
Restart sshd manually.

```yaml
- hosts: all
  roles:
    - role: ssh
```
