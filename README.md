# Ansible-LAMP-Ubuntu18.4
An Ansible provisioning script for installing PHP 7.4 along with MySql and Apache 2.4 onto an Ubuntu 18.04 box.

# Instructions

By default, the master branch of this repository will install php7.4. 

If you'd prefer php8.0, simply checkout the branch named `php-versions/php-8` and provision.

- Requires Virtual Box - https://www.virtualbox.org/wiki/Downloads
- Requires Vagrant - https://www.vagrantup.com/

Clone the repository and simply run `vagrant up`.

The `sites/` directory is synced to `/vagrant` within your virtual machine so add your sites into here.

Template Vhosts can be created to automate the setting up of your sites.

# PHP Installs
- PHP 7.4
- PHP 7.4-xml
- PHP 7.4-curl
- PHP 7.4-intl
- PHP 7.4-zip
- PHP 7.4-soap
- PHP 7.4-mbstring
- PHP 7.4-bcmath
- PHP 7.4-gd

Composer will also be globally installed.

# mySql

- Username: `root`
- password: `123`



