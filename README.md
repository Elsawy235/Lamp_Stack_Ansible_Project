# Lamp_Stack_Ansible_Project
# Ansible LAMP Stack Playbook
This is a Ansible Playbook to deploy a LAMP Stack infrastructure on ubuntu/debian hosts. 

### Stack -
* apache--http
* mysql 
* php7.0-fpm

### Pre-requisites
You must have Ansible installed.

### Setup
* Add host in /root/ansible/ansible_project/inventories/hosts file. See the given hosts file to add hosts.  
* Run command `ansible-playbook main.yml -i inventories/hosts
  
