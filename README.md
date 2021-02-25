memoryleak.bash
===============

A basic role to configure bash.

Requirements
------------

None

Role Variables
--------------

```
bash_ps1: |
  "\[\e[32m\]\u\[\e[m\]@\[\e[31m\]\h\[\e[m\]:[\[\e[35m\]\W\[\e[m\]]: "

bash_aliases:
  - name: mountt
    value: "mount | column -t"
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: memoryleak.bash }

License
-------

MIT

Author Information
------------------

Haydar Ciftci <haydar.ciftci@gmail.com>
