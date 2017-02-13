# Kubeadm-Ansible

Ansible scripts to create & destroy a Kubernetes cluster using kubeadm.

## Howto
- Create a hosts file (check the example)
- Create a vars.yaml (check the example)
- To create a cluster: `ansible-playbook -i hosts create.yaml` 
- To destroy the cluster: `ansible-playbook -i hosts destroy.yml`
