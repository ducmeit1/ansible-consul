# Install Consul Cluster with Ansible Playbook

This ansible playbook helps you deploy consul cluster with multiple optionals

## Install Ansible

- Install Ansible on Debian Host Machine:

    ```shell
    sudo apt update -y
    sudo apt install -y git software-properties-common
    sudo apt install -y python-pip
    sudo pip install -r requirements.txt
    echo 'deb http://ppa.launchpad.net/ansible/ansible/ubuntu trusty main' | sudo tee -a /etc/apt/sources.list
    sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367
    sudo apt update -y
    sudo apt install ansible -y
    ```
    
- Install Ansible on Ubuntu Host Machine:
    
    ```shell
    sudo apt update
    sudo apt install -y git software-properties-common
    sudo apt install -y python-pip
    sudo pip install -r requirements.txt
    sudo apt install -y dirmngr
    sudo apt-add-repository --yes --update ppa:ansible/ansible
    sudo apt install -y ansible
    ```

# Ansible-Playbook

- Use ansible-playbook to run with examples:

    ```shell
    ansible-playbook site.yml
    ```