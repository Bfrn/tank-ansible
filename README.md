# Ansible Playbooks for deplying Tank cluster

## Prequisites

Install Ansible >= 2.8  
https://docs.ansible.com/ansible/2.8/installation_guide/intro_installation.html

Control node needs to have ssh key-auth access to all nodes, including tank, cassandra, proxy and later on memcached nodes

## Usage

`ansible-playbook -i hosts site.yml`  
`ansible-playbook -i hosts tank_nodes.yml`  

Prometheus Node Exporter 0.15 will be installed, make sure to use the matching Grafana Dashboard template (e.g. https://grafana.com/dashboards/7039).

## Roles

TODO: describe roles

