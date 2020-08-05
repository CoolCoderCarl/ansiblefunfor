### Ansible Role: honeypot

Create a brute force protection

**Original instruction - https://nxnjz.net/2019/11/how-to-set-up-an-interactive-ssh-honeypot-on-centos-8/**

### Requirements

`become` must be true
`gather_facts` must be true

### Role Variables

Cowrie home
`git_cowrie_home` contain all files for cowrie launch

SSH port  
`ssh_port` custom ssh port

### Example

`ansible-playbook playbooks/deployforkbomb.yaml -i inventories/hosts`