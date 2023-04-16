joenyland.homeshick
=========================

[![CI](https://github.com/JoeNyland/ansible-homeshick-role/actions/workflows/ci.yml/badge.svg)](https://github.com/JoeNyland/ansible-homeshick-role/actions/workflows/ci.yml)

Installs homeshick and links dotfiles.

Requirements
------------

None.

Role Variables
--------------

### `homeshick_dotfiles_repos`

Dotfiles repos to clone and link.

### `homeshick_version`

Which version of Homeshick to install. Defaults to HEAD.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: server
  roles:
    - role: joenyland.homeshick
      vars:
        homeshick_dotfiles_repos:
          dotfiles: git@github.com:user/dotfiles.git
```

License
-------

MIT

Author Information
------------------

⌨️ with ❤️ by [Joe Nyland](https://joe.nyland.io)
