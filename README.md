# Install Consul Cluster with Ansible Playbook

This ansible playbook helps you deploy consul cluster with multiple optionals

## Install Ansible

- Install Ansible on Debian Host Machine:

    ```shell
    sudo apt update -y
    sudo apt install -y git software-properties-common
    echo 'deb http://ppa.launchpad.net/ansible/ansible/ubuntu trusty main' | sudo tee -a /etc/apt/sources.list
    sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367
    sudo apt update -y
    sudo apt install ansible -y
    ```

# Ansible-Playbook

- Use ansible-playbook to run:

    ```shell
    ansible-playbook site.yml
    ```