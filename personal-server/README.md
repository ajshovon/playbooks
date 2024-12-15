```bash

# List Hosts
ansible-playbook --list-hosts 10_install_packages.yml

# Run playbook
ansible-playbook 10_install_packages.yml

# List Tasks
ansible-playbook ansible-playbook --list-tags

# Run with tags
ansible-playbook --tags firewall 10_install_packages.yml
```