# Ansible-LAMP-Ubuntu18.4
An Ansible provisioning script for installing PHP 7.3 along with MySql and Apache 2.4 onto an Ubuntu 18.04 box.

# Instructions

- Requires Virtual Box - https://www.virtualbox.org/wiki/Downloads
- Requires Vagrant - https://www.vagrantup.com/

Clone the repository and simply run `vagrant up`.

The `sites/` directory is synced to `/vagrant` within your virtual machine so add your sites into here.

Template Vhosts can be created to automate the setting up of your sites.

# PHP Installs
- PHP 7.3
- PHP 7.3-xml
- PHP 7.3-curl
- PHP 7.3-intl
- PHP 7.3-zip
- PHP 7.3-soap
- PHP 7.3-mbstring
- PHP 7.3-bcmath
- PHP 7.3-gd

Composer will also be globally installed.

# mySql

- Username: `root`
- password: `123`



