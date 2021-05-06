Role Name
=========

Slavecon -  This role will configure slave nodes on your launched EC2 instances by installing kubeadm, kubelet and kubectl and joining the nodes with the master node.

Requirements
------------

Pre-requisites:
1. Linux Os
2. Ansible installed
3. Python3 

Role Variables
--------------

Just one : `cidr: "17.100.0.0/16"` that is for flannel configuration.


Dependencies
------------

This role will work efficiently after running the `Mastercon` role present in the repo.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: rolename }

License
-------

BSD-3-Clause


