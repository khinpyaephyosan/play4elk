Role Name
=========

A small note for installing and configuring elk

Role Variables
--------------

can change kibanaadmin password under vars/main.yml (kibana_admin.name and kibana_admin.pw)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    - hosts: node1
      roles:
        - role: elk
          when: ansible_processor_vcpus == 1 and ansible_memtotal_mb >= 2048 and ansible_processor_vcpus == 1 and  ansible_os_family == 'RedHat'
    ...
License
-------

BSD

Author Information
------------------

https://www.linkedin.com/in/lillian-phyoe-a4485113a/
