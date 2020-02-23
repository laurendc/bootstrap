Role Name
=========

This installs Homebrew packages.

Requirements
------------

*  Homebrew: `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Role Variables
--------------

`brew_packages` for all homebrew packages that AREN'T cask installations.

`brew_cask_packages` are for all homebrew cask installations.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: brew_packages }

License
-------

MIT

Author Information
------------------

Lauren Caliolio (laurendc[at]gmail[dot]com)
