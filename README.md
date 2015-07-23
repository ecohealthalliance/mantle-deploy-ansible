Ansible deployment for Mantle.

### Deploying to an AWS instance

Edit the inventory.ini file to add instance ip addresses you want to deploy to.
Then run a command like this:

```
ansible-playbook site.yml -i inventory.ini --private-key ~/.keys/infrastructure.pem
```
