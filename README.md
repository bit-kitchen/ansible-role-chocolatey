ansible-role-chocolatey
=======================

[![Ansible Role: bit_kitchen.chocolatey](https://img.shields.io/ansible/role/46873.svg)](https://galaxy.ansible.com/bit_kitchen/chocolatey)
[![Build Status](https://travis-ci.org/bit-kitchen/ansible-role-chocolatey.svg?branch=master)](https://travis-ci.org/bit-kitchen/ansible-role-chocolatey)

Install [chocolatey](https://chocolatey.org/).

This role will do nothing on Linux, so that it can be depended on by roles compatible with both Linux and Windows.

    ansible-galaxy install bit_kitchen.chocolatey

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: win_servers
      roles:
        - bit_kitchen.chocolatey

License
-------

[MIT](LICENSE)

Author Information
------------------

[bit.kitchen](https://github.com/bit-kitchen)
