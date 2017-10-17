Role of installing Wicked PDF
=========

Wicked PDF tools ansible galaxy role.

Requirements
------------

None

Role Variables
--------------

* wickedpdf_wkhtmltopdf_download_url  
wkhtmltopdf download url

* wickedpdf_wkhtmltopdf_version  
wkhtmltopdf version

Dependencies
------------

None

Example Playbook
----------------

```yml
---
- hosts: all
  become: true
  roles:
    - { role: wickedpdf }
```

License
-------

BSD

Author Information
------------------

[Daisuke Maeda](https://github.com/dmae3 "Daisuke Maeda")
