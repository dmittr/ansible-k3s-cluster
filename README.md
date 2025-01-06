# ansible-k3s-cluster
ansible role for k3s cluster

## Usaage
Define the desired hosts into a group (e.g. k3s) and assign cluster-roles in playbook files or somewhere else.

While the playbook is running, k3s will initialize the cluster on the k3s_init host and connect the other nodes to it. You only need to connect to the cluster using /etc/rancher/k3s/k3s.yaml. 
