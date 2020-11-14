# ansible_docker_linux
Ansible playbooks to install docker and docker compose on linux servers

First, you can clone git repository:

    git clone https://github.com/oskarpilch/ansible_docker_linux.git

and go to the folder:

    cd ansible_docker_linux
  
Then, you can modify file inventory/hosts with your IP addresses.
  
Once you're there you can run followning commands:

  1) Ubuntu:
  
    ansible-playbook -i inventory/hosts playbook/docker_ubuntu.yml
    
  2) CentOS:
  
    ansible-playbook -i inventory/hosts playbook/docker_centos.yml
    
