[![Build Status](https://travis-ci.com/IRMooBear/install_uhubctl.svg?branch=master)](https://travis-ci.com/IRMooBear/install_uhubctl)

Install UHubCTL
=========

This is an ansible role that install the uhubctl utility.

Variables
------------
Set the git release version of uhubctl to clone.

    uhubctl_version: "v2.0.0"


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: irmoobear.install_uhubctl }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).