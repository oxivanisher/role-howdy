howdy
=====

This role installs [howdy](https://github.com/boltgolt/howdy). Please be aware, that the package is installed without being configured. You will have to run `sudo howdy config` to set it up.

Example Playbook
----------------
```yaml
- name: Install howdy
  hosts: client
  collections:
    - oxivanisher.linux_desktop
  roles:
    - role: oxivanisher.linux_desktop.howdy
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_desktop](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_desktop/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_desktop).
