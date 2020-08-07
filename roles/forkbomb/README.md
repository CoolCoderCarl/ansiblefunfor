# Ansible Role: forkbomb

Role deploy shell script and set cron job for it

**This code can cause significant harm to computers and disable entire systems**

**Do not run this playbook in an industrial or other environment where people work**

**Use this only for experiments in a closed system where only you**

## Requirements

`become` must be true

## Role Variables

Minutes  
`min` - set minute for cron job

Hours  
`hour` - set hour for cron job

## Example

`ansible-playbook playbooks/deployforkbomb.yaml -i inventories/hosts`