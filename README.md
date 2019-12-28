# Ansible

This is good for provisioning and automation, it will improve scalability, consistency and reliability in the IT environment

## How to install ansible with Ubuntu
  - sudo apt-get install software-properties-common
  - sudo add-apt-repository ppa:ansible/ansible
  - sudo apt-get update
  - sudo apt install ansible


## Check ansible files
- from ubuntu you want to cd into /etc/Ansible
  - check to see if there is something along the lines of vars or roles
    - if not: sudo mkdir -p /usr/local/etc/ansible/group_vars

- also check to see if there is a hosts file
  - if not: sudo touch /usr/local/etc/ansible/hosts

**Hosts** file should contain your ansible inventory
**group_vars** should contain the ansible playbook variables

## Configuring file for ansible

- etc/ansible/ansible.confi

- use the command **sudo vim** to get into this file

- Unhash **inventory** and **sudo_user**

- to save **ctrl C**, then **:x**


## How to run the app

1. if you have not then you need to install ansible on ubuntu
2. check to see that ansible has been installed
3. Go to environment and then run the playbook using **ansible-playbook <name of playbook>** this should be a .yml file
4. cd into the app and then run **npm start**
5. Check to see if the website loads 
