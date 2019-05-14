# ansible-role-vnstat
Install and enable vnstat on Ubuntu or Red Hat

## Requirements

- Your playbook must gather facts
- Ubuntu: >= 16.04
- RedHat/CentOS: >= 6.10 with Epel


## Role Variables

None


## Dependencies

None

## Example Playbook

```yaml
    - hosts: mygroup
      gather_facts: true
      become: true
      roles:
        - name: Collect lightweight network stats
          role: acromedia.vnstat
```


## License

GPLv3


## Author Information

Acro Media Inc.
