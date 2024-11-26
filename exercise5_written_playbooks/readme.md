ansible-playbook -i inventory.yml web-db.yml
ansible-playbook -i inventory.yml web-db.yml -v
ansible-playbook -i inventory.yml web-db.yml -vv
ansible-playbook -i inventory.yml web-db.yml -vvv
ansible-playbook -i inventory.yml web-db.yml --syntax-check

### Dry run
ansible-playbook -i inventory.yml web-db.yml -C