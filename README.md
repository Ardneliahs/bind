Role Name
=========

This role installs bind server on Debian.


Role Variables
--------------



vars defined  for bind in vars/main.yaml



domain: shailendra.local

rev_domain: 0.168.192.in-addr.arpa

sub_range: 192.168.0.0/24

mappings:

      - host: test

        ip: 192.168.0.1

      - host: test2

        ip: 192.168.0.10



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

