# Gogs on CentOS Ansible script

This sets up [Gogs](https://gogs.io/) on [CentOS](https://www.centos.org/) 7.2. 

## Usage

1. Copy and edit the inventory with the ip address of the target machine.

        $ cp inventory.example inventory

2. Run the ansible playbook

        $ ansible-playbook playbook.yml -i inventory


## License

MIT