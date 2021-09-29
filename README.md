# Ansible

This is my ansible repository for anything. At the moment, I only created files to deploy my local k8s cluster.

## Command to deploy k8s-local playbook

 - `$ ansible-playbook --become --inventory production/hosts k8s-local.yaml --ask-vault-pass PASSWORD`
 - `$ ansible-playbook --become --inventory production/hosts k8s-local.yaml --vault-password-file PASSWORD_FILE`
