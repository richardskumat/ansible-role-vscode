Vscode ansible role
=========

Installs Microsoft's VSCode.

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

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vscode }

License
-------

GPLv3

Author Information
------------------

Richard Skumat

Link:

https://github.com/richardskumat