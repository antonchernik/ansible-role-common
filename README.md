Common
=========

Ansible role for common tools and libraries. Tested platforms are:
* Debian 8

Role install packages:
vim, htop, cron, zip, unzip, wget, curl, mc, sudo, apache2-utils, ipset, git, fail2ban, gcc, g++, network tools etc.

Requirements
------------

Debian 8 (jessie)

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

default_locale: ru_RU.UTF-8

Variable set default system locale

default_timezone: Europe/Kiev

Variable set default system timezone

Dependencies
------------

None

Example 
----------------
    ---
    - hosts: all
      roles:
         - { role: antonchernik.common }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2017 by [Anton Chernik](https://github.com/antonchernik).
