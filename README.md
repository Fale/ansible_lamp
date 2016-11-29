# Ansible LAMP example

## Run

### Provision

    ansible-playbook --vault-password-file ~/.ssh/ansible_vault_key.txt playbooks/provision_do_cf.yaml

### First run

    ansible-playbook playbooks/firstrun.yaml

### Run

    ansible-playbook master.yaml

### Teardown

    ansible-playbook --vault-password-file ~/.ssh/ansible_vault_key.txt playbooks/teardown_do_cf.yaml

