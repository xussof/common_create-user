common_create-user
=========

This role will create a user on selected machine.
Can be root or not

Requirements
------------

All dependencies will appear on requirements.yml file

Role Variables
--------------

#dict_common_create_user:
#  jenkins:
#    user_name: jenkins
#    user_shell: /bin/bash
#    user_home: /home/jenkins
#    is_sudo: True
#  xussof:
#    user_name: xussof
#    user_shell: /bin/bash
#    user_home: /home/xussof
#    is_sudo: True


Dependencies
------------

All dependencies will appear on requirements.yml file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: common_create-user }

License
-------

BSD

Author Information
------------------
Made by @sergi-canas
