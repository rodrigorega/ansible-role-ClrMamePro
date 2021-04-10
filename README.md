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

    - hosts: localhost
      connection: local
      roles:
        - { role: rodrigorega.ansible_role_clrmamepro, clrmamepro_final_user: john_doe }

Run the playbook with: "ansible-playbook clrmamepro.yml"

License
-------

CC-BY

Author Information
------------------

- You can contact me at rodrigorega@gmail.com
- My website: http://rodrigorega.es
