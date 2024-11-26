ansible web01 -i iventory.yml -m ping
ansible web01 -i inventory.yml -m ping
ansible db01 -m ping -i inventory.yml
ansible all -m ping -i inventory.yml