# Ansible: Ruby on Rails Environment
Use this ansible playbook to setup a fresh development environment with the following components:

* Rbenv
* Ruby
* MySQL
* Memcached
* Redis
* Tools (tmux, vim, htop, git, wget, curl etc.)

## Prerequisites & Config
1. Replace `<your_user>` in ```site.yml```.
2. Modify the contents ```group_vars/all```.


## Install Playbook

Run ```ansible-playbook site.yml -i hosts --extra-vars "ansible_sudo_pass=<your_password>"```.
