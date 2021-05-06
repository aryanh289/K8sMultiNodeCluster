Role Name
=========

Mastercon -  This role will configure a master node on your launched EC2 instance by installing kubeadm, kubelet and kubectl and initialising all the required pods on the docker container.

Requirements
------------

Pre-requisites:
1. Linux Os
2. Ansible installed
3. Python3 

Role Variables
--------------

Just one : `cidr: "17.100.0.0/16"` that is for flannel configuration.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: rolename }

License
-------

BSD-3-Clause


