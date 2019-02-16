play4elk
=========

A small note for installing and configuring elk

Variables
---------

can change kibana access under vars/main.yml (kibana_admin.name and kibana_admin.pw)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    - hosts: node1
      roles:
        - role: play4elk
          when: ansible_processor_vcpus == 1 and ansible_memtotal_mb >= 2048 and ansible_processor_vcpus == 1 and  ansible_os_family == 'RedHat'
    ...
    
Author Information
------------------

https://www.linkedin.com/in/lillian-phyoe-a4485113a/


Reference
---------
https://www.digitalocean.com/community/tutorials/how-to-install-elasticsearch-logstash-and-kibana-elk-stack-on-centos-7
