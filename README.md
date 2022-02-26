# Ansible-Kube
Setup Kubernetes Cluster using Ansible Playbooks and Roles 

## Roles
- Docker : To setup docker in worker nodes
- Kubernetes : Setup kubernetes using worker nodes

## Command
ansible-playbook --vault-password-file=".secret"  -i ./hosts kube.yml

