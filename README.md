[![Build Status](https://travis-ci.com/IRMooBear/ansible.uhubctl.svg?branch=master)](https://travis-ci.com/IRMooBear/ansible.uhubctl)

Install uhubctl
=========

This is an ansible role that install the uhubctl utility.

Dependencies
------------
This role build uhubctl from source from https://github.com/mvp/uhubctl.

Variables
------------
Set the git release version of uhubctl to clone.  Change this as uhubctl updates.

    uhubctl_version: "v2.0.0"

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: irmoobear.install_uhubctl, uhubctl_version: "v2.0.0" }

License
-------

BSD

Author Information
------------------

anh ( then the at sign ) anh nguyen (without the space) . name (yeah, .name)