# ansible


## Config Files
Ansible will reference a config file in the following order (and stops looking once one is found)  

* ANSIBLE_CONFIG (environment variable if set)
* ansible.cfg (in the current directory)
* ~/.ansible.cfg (in the home directory)
* /etc/ansible/ansible.cfg

ANSIBLE_CONFIG (Environment Variable)
ansible.cfg (current directory)
ansible.cfg (home directory)
/etc/ansible/ansbile.cfg
