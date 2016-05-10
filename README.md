Calico Ansible Role
=========

[![Build Status](https://travis-ci.org/lucazz/ansible-calico.svg?branch=master)](https://travis-ci.org/lucazz/ansible-calico)

A brief description of the role goes here.

Requirements
------------

This role only requires Ansible version 2+

Role Variables
--------------

These are the variables that you can override anywhere in your playbook flow:

ETCD version installed on your host:
etcd.port: 2379

Calico version you want to install:
calico.version: 1.2.0

Dependencies
------------

This role depends on:

 * [lucazz.etcd](https://github.com/lucazz/ansible-etcd)


Example Playbook
----------------

Using this roles as as simples as:

- hosts: servers
      roles:
         - lucazz.etcd
         - lucazz.calico

License
-------

BSD

Author Information
------------------
Lucas do Amaral Saboya Works as Site Reliability Engineer @ [HE:labs](https://www.helabs.com)
