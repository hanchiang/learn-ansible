# Introduction

This repository demontrates the use of ansible using playbook and roles, in `playbook/` and `roles/` directories respectively with VMs deployed in AWS

# Set up

First, set up the VMs and write the IP addresses in `hosts` file

**Install ansible**: https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html  
**Run from `playbook/`**: `ansible-playbook -i hosts playbook.yml`  
**Run `roles/`**: `ansible-playbook -i hosts roles/site.yml`
