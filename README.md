# devstack
## Prerequisites:
1. Make sure openstacksdk is installed:
```
pip install --user openstacksdk
```
## Input:

## Use the ansible playbook to
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


## Parameters:
All the variables are stored in var/params.yml

## Run the playbook:
ansible-playbook -i hostslocalDevstack main.yml


## Tests:
Playbooks havent been tested against:
- Ansible 2.7.0, 2.8.0.dev0
- Openstack Pike, queens (devstack)

## Improvement:
