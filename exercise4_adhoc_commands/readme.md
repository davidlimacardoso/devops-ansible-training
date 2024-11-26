### Install
ansible webservers -m ansible.builtin.yum -a "name=httpd state=present" -i inventory.yml --become

### Remove
ansible webservers -m ansible.builtin.yum -a "name=httpd state=absent" -i inventory.yml --become

### Start httpd Service
ansible webservers -m ansible.builtin.service -a "name=httpd state=started enabled=yes" -i inventory.yml --become

### Copy index to destination webservers
ansible webservers -m ansible.builtin.copy -a "src=index.html dest=/var/www/html/index.html" -i inventory.yml --become