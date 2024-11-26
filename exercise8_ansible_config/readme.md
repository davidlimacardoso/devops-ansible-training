sudo touch /var/log/ansible.log
sudo chown ubuntu:ubuntu /var/log/ansible.log
ansible-playbook db.yml
tail /var/log/ansible.log