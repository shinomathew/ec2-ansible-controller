Spin up an ec2 instance that can be used as Ansible controller node
===================================================================

This is an ansible playbook that spins up an ec2 instance (Centos) with that can be used as an ansible controller.


Requirements
------------

* Ansible and python
* AWS credentials available (as aws profile or environment variables)

Usage
-----
`ansible-playbook ansible_control_node.yaml -i inventory.yaml`


