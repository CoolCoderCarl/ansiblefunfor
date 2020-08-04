### Ansible Role: forkbomb

Role deploy shell script and set cron job for it

### Requirements

`become` must be true

### Role Variables

Minutes  
`min` - set minute for cron job

Hours  
`hour` - set hour for cron job

### Example

`ansible-playbook playbooks/deployforkbomb.yaml -i inventories/hosts`