Vsftpd Installs on RHEL/Debian or based OS
=========

This playbook will install vsftpd, will configure port 2120 with anonymous login on and local users of OS will works fine.

Requirements
------------

- OS Rhel based
- OS Deb based

Role Variables
--------------

This Playbook will use just facts of Ansible, import_tasks, and will gotcha everything from a main playbook, everything will be referenced at tests/test.yml for a correct run, more details will be described below.

Dependencies
------------

You will not need have any another playbook or thing, this playbook is complete, and all content of config files for example, are attached at files/templates.

Example Playbook
----------------

This playbook need be executed from tests directory with command `ansible-playbook -i /etc/ansible/inventories/testing/ test.yml` for example, there is the test.yml content:

    - hosts: all
      roles:
         -  role: ../..

License
-------

GNU

Author Information
------------------

Hello, i am Igor, a IT & Infosec Expert, linux entusiastic and some sysadm/devops skills.  
