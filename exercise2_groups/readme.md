ansible webservers -m ping -i inventory.yml
ansible databases -m ping -i inventory.yml
ansible dc_east -m ping -i inventory.yml