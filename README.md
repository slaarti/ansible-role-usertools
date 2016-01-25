# User Tools Role

This is just a simple ansible role to install some packages I like to have.

Role Variables
--------------

    usertools_packages: []

The list of packages to install. Rather than pushing an update to github
and re-installing the role every time I decide to add a package to
a hard-coded list, I decided to switch to a variable that I can set in my
playbook repo.

Example Playbook
----------------

    - hosts: servers
      roles:
         - slaarti.usertools

License
-------

Unlicense; see the LICENSE file.

Author Information
------------------

Chris Pinard <slaarti@gmail.com>
