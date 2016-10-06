# Islandora 7.x.: Ansible

This ansible playbook installs [vagrant version of Islandora 7.x.](https://github.com/Islandora-Labs/islandora_vagrant)

This ansible playbook has been tested using Ubuntu 14.04

# Setup

Clone this repository locally, edit `hosts` in install-islandora-7.x.yaml to where you want to install.

```bash
git clone https://github.com/jefferyb/islandora-7.x-ansible-installer.git
cd islandora-7.x-ansible-installer
ansible-playbook install-islandora-7.x.yaml
```

If you want to switch some settings, edit islandora-7.x-ansible-installer/roles/install-islandora-7.x/vars/main.yml

# Contributing

I'm still new to the project, learning the ins & outs, so if you use it and find some bugs or way to improve the setup,
please don't hesitate to contact me/contribute...
