BIND
---------

This role installs bind server on Debian.


Role Variables
--------------

vars are defined  for bind in vars/main.yaml



Example Playbook
----------------

	- name: Set up Bind

	  hosts: bind

	  gather_facts: true

	  become: true



	  roles:

	    - bind



License
-------

BSD

