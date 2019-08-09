SLAPD
=========
```
- name: playbook
  hosts: ldap
  roles:
    - slapd
```

How to use
------------------
```
ansible-playbook -i inventory playbook.yml -e rootpw=tibo -e dcname=tibo
```
