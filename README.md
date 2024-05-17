# Nginx on Ansible 

On this repository we have basic configuration to deploy a basic nginx server on ansible.

## Previus steps
- Have 4 machines in the same network
 - Hosts (1)
 - Servers (3)
- SSH connection as root allowed on the servers
- Servers and hosts updated
- Have installed ansible on our host machine

## How to deploy de service
- Step 1: Change hosts configurations using on servers your own IP and change SSH user and password configuration.
- Step 2: Run playbook by the following command ansible-playbook yml_file -i ansible_hosts_file.
- Step 3: Try to connect to the servers IP on navigator or with curl command by using the host machine.
