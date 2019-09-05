mutifile-handle
=========

you can use it to handle muti files



Role Variables
--------------

paths: you file path
patterns: regx rules

Example Playbook
----------------

```yaml
- hosts: localhost
  roles:
    - mutifile-handle
```

you can to run

```bash
ansible-playbook play.yaml -e paths="/opt/charts/stable" -e patterns=".*.tpl"
```


License
-------

BSD

Author Information
------------------

you can touch me in my [website](https://www.li-rui.top/)
