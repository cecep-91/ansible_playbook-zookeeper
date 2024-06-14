# Ansible Playbook for Setting Up a Zookeeper Cluster on Ubuntu Server
## Prerequisites:
- ansible
- sshpass

## Instructions:
1. Clone the repository.
2. Navigate to the root directory of the repository.
3. Edit the 'hosts' file. List the servers where you intend to install the Zookeeper cluster in the '[zookeeper_server]' section. Ensure to define the root password for the servers.
4. Modify the 'setup_zookeeper.yaml' file. Adjust the Zookeeper configurations in the 'vars:' section as needed.
5. Execute the playbook using the command ansible-playbook setup_zookeeper.yaml.