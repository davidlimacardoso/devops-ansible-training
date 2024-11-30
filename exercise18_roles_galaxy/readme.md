ansible-galaxy init post-install
ansible-playbook provisioning.yml
ansible-playbook provisioning.yml --check
ansible-playbook provisioning.yml --check --diff

### https://galaxy.ansible.com/ui/standalone/roles/geerlingguy/java/documentation/
ansible-galaxy role install geerlingguy.java