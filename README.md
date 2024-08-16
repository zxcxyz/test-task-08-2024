# How to run and test
## prerequisites
- ansible
- a linux host for testing, or Vagrant with virtualbox installed for a local VM

```bash
# dependencies
ansible-galaxy install -r requirements.yaml 

# testing with vagrant
vagrant up
ansible-playbook playbook.yaml

# ssh on vagrant to test 
vagrant ssh
```