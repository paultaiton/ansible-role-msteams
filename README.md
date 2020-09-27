Role Name
=========

Install Microsoft Teams on Fedora Linux via Microsoft's yum repository.

Requirements
------------

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

		- name: MS Teams Role
		  hosts: all
		  become: yes
		  roles:
		    - paultaiton.msteams

License
-------

GPL 3.0 or later.

Author Information
------------------

@paultaiton on github.
