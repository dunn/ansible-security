ansible-security
================

Improve networking security on RHEL/CentOS

Variables
---------

- `deploy_user` the user you SSH in as; defaults to `deploy`.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: all
  roles:
    - { role: dunn.security, become: yes }
```

License
-------

MIT
