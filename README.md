# Bootstrap Cloud VM

The repository is connected to a Terraform plan that initializes and configures the virtual machine using Ansible:

    ~/.local/bin/ansible-playbook --connection=local --inventory localhost, playbook.yml
