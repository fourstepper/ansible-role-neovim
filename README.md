ansible-role-neovim
=========

This role installs and configures Neovim, including dependencies for coc-nvim to work

Requirements
------------

A neovim configuration folder at files/nvim (can be taken directly from $HOME/.config/nvim)

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: localhost
      roles:
         - role: ansible-role-neovim

License
-------

BSD
