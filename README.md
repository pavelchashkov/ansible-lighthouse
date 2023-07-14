Lighthouse
=========

This role can install Lighthouse with nginx on EL

The LightHouse repository is located [link](https://github.com/VKCOM/lighthouse).

Example Playbook
----------------

```yaml
- name: Install Lighthouse
  hosts: lighthouse
  tags:
    - lighthouse
  roles:
    - lighthouse
```

License
-------

MIT

Author Information
------------------

Pavel Chashkov
