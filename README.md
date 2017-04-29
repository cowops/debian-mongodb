Debian-Mongodb
==============

MongoDB (from "humongous") is an open-source document database, and the leading NoSQL database.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-mongodb }

Tasks
-----

  - Install [MongoDB](http://www.mongodb.org/)


License
-------

BSD
