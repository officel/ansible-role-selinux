Ansible Role: selinx
=========

[![Build Status](https://travis-ci.org/officel/ansible-role-selinux.svg?branch=master)](https://travis-ci.org/officel/ansible-role-selinux)
[![Ansible Role](https://img.shields.io/badge/galaxy-officel.selinux-blue.svg?maxAge=2592000)](https://galaxy.ansible.com/officel/selinux/)

disable selinux.

Requirements
------------

none.

Role Variables
--------------

none.

Dependencies
------------

none.

Example Playbook
----------------

    - hosts: all
      become: yes
      roles:
         - officel.selinux

License
-------

MIT / BSD

Author Information
------------------

This role was created by raki.
