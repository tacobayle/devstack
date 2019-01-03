# devstack
Goals:
- Install devstack in a single host
- Configure OpenStack with networks, subnets, security groups, ...
- Spin up a couple of VMs

Use the following command:
- ansible-playbook -i hostAzurePrivate installDevstack.yml ; ansible-playbook ConfigureDevstack.yml

All the variables are stored in var/params.yml

Prerequisites:

Script has been tested against:
- Ansible 2.7.0
- Ubuntu 16.04.05 LTS (locally Vmware and in Azure)
