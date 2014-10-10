
* Vagrant

vagrant up

* Ansible

Running an ad-hoc command (uptime):
ansible -i hosts bookstore -a "uptime"

Running the bookstore playbook:
ansible-playbook -i hosts bookstore.yml
