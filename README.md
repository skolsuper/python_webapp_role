Role Name
=========

This role uses supervisor to up gunicorn workers listening on 127.0.0.1 port 8000 (default).  You will want to put these behind a reverse proxy/load balancer such as Nginx.

Requirements
------------

None

Role Variables
--------------



Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
