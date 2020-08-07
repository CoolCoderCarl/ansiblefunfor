# Ansible Role: honeypot

Deploy a brute force protection for CentOS 8

**Original instruction - https://nxnjz.net/2019/11/how-to-set-up-an-interactive-ssh-honeypot-on-centos-8/**

## Requirements

`become` must be true
`gather_facts` must be true
`firewall` must be operation

Set `ansible_port=1269` for `ssh-defends` group after installation 

## Role Variables

Cowrie home  
`git_cowrie_home` contain all files for cowrie launch

SSH port  
`ssh_port` custom ssh port, default is `1269`

## Example

`ansible-playbook playbooks/deployforkbomb.yaml -i inventories/hosts`
