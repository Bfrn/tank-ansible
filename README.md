# Ansible Playbooks for deplying Tank cluster

## Prequisites

Install Ansible >= 2.8  
https://docs.ansible.com/ansible/2.8/installation_guide/intro_installation.html

Control node needs to have ssh key-auth access to all nodes, including tank, cassandra, proxy and later on memcached nodes

## Usage

`ansible-playbook -i hosts site.yml`  
`ansible-playbook -i hosts tank_nodes.yml`  

The Prometheus Node Exporter is installed on all nodes, the version can be controlled using the variables for its ragarding role.

## Roles

TODO: describe roles

