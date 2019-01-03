# devstack
Goals:
- Install a new devstack in a single host

Use the following command  to create the infratructure:
- ansible-playbook -i hostAzurePrivate installDevstack.yml

All the variables are stored in var/params.yml

Prerequisites:

Script has been tested against:
- Ansible 2.7.0
- Ubuntu 16.04.05 LTS
