# ansible-redmine
Ansible deployment of Redmine V2.5.1 issue tracker with Backlog v1.0.6 plugin on Ubuntu 14.04
*http://www.redmine.org/*
*http://www.redminebacklogs.net/*

## Vagrant test :
*For Vagrant test environment, install Vagrant, Ansible and Virtualbox*
*Vagrant uses "hostmanager" plugin. Before running, install with: `vagrant plugin install vagrant-hostmanager`*

To spin up Redmine VM run:

`vagrant up`

Redmine interface will then be located at:

http://redmine.internal.tld

username: admin pass: admin

edit `inventory/group_vars/all.yml` to change passwords

