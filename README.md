Ansible Role: Tomcat
=========

Installs and configures the Apache Tomcat webserver.

Requirements
------------

Java - the current versions of Tomcat (7.0.x or 8.5.x) requires Java Runtime Environment (JRE) version 1.6 or higher (1.7 for websockets).

Role Variables
--------------

TBD

Dependencies
------------

Any role (or other method) that will provide Java

Example Playbook
----------------

- hosts: tomcat
  roles:
     - { role: java }
     - { role: tomcat }

License
-------

CC0

Author Information
------------------

Drew Heles
