BIND
---------

This role installs bind server on Debian.


Role Variables
--------------

vars are defined in vars/main.yaml for bind.



Example Playbook
----------------

	- name: Set up Bind server

	  hosts: bind

	  gather_facts: true

	  become: true



	  roles:

	    - bind



License
-------

BSD

