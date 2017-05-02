ClrMamePro
=========

Install ClrMamePro in Debian Jessie using Wine.

Requirements
------------

No Requirements.

Role Variables
--------------

Edit "defaults/main.yml" and change the variable "clrmamepro_final_user" to match the user that will run ClrMamePro. Or if you use the example playbook you can set this variable without editing "defaults/main.yml".

Dependencies
------------

No dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      connection: local
      roles:
        - { role: ansible-role-ClrMamePro, clrmamepro_final_user: john_doe }

License
-------

CC-BY

Author Information
------------------

You can contact me at rodrigorega@gmail.com
My website: http://rodrigorega.es
