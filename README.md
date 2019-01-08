# devstack
Goals:
- Install devstack in a single host
- Configure OpenStack with networks, subnets, routers for provider project
- Upload OpenStack image
- Configure OpenStack with networks, subnets, routers for tenant project
- Configure OpenStack with Security Groups for tenant project
- Configure Ssh key
- Create VM servers category
- Create VM clients category
- output a file inventory with server IPs

Use the following command:
- ansible-playbook -i hostAzurePrivate installDevstack.yml ; ansible-playbook configureDevstack.yml

All the variables are stored in var/params.yml

Prerequisites:

Script has been tested against:
- Ansible 2.7.0
- Ubuntu 16.04.05 LTS (locally Vmware and in Azure)
- Openstack Pike (devstack)
