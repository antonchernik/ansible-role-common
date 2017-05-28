Common
=========

Ansible role for common tools and libraries. Tested platforms are:
* Debian 8

Requirements
------------

Debian 8

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

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: antonchernik.common }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2017 by [Anton Chernik](https://github.com/antonchernik).
