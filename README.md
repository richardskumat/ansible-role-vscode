Vscode ansible role
=========

Installs Microsoft's VSCode based on
https://code.visualstudio.com/docs/setup/linux.

Requirements
------------

Tested with latest ansible(2.8.3).

Ansible > 2.8

Role Variables
--------------

```
# defaults file for vscode
# valid values: present, absent
# present installs the role
# absent removes everything that the role touches
vscode_installed_state: present
# valid values are
# code for stable release
# code-insiders for beta
vscode_package_name: code

# determines the files name that gets added to
# /etc/apt/sources.list.d
vscode_apt_file_name: vscode
```

Dependencies
------------

X11 graphical environment where this role ends up being installed.

License
-------

GPLv3

Author Information
------------------

Richard Skumat

Gitlab:

https://gitlab.com/richardskumat/ansible-role-vscode

Gitlab-ci:

https://gitlab.com/richardskumat/ansible-role-vscode/pipelines

Github:

https://github.com/richardskumat/ansible-role-vscode

Travis:

https://travis-ci.org/richardskumat/ansible-role-vscode
