# THIS PROJECT IS A BUNCH OF TESTS FOR DEPLOYMENT STRATEGIES

## If you are using Ansible

### Prerequisites

- Digital Ocean droplet with public ip
- Python3 and Ansible installed in control and managed node with the same version

### How to start

> Fill the inventory.yml with a real public ip and then run the following command

```
ansible-playbook -i inventory.yml playbook/deploy.yml
```
