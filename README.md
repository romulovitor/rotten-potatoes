# Web system in kubernets

This project provides an infra-structure to run a web system on kubernets

## Dependencies
- K3d
- Kubectl

## commands
- kubectl apply -f k8s/mongodb/deployment.yaml
- k3d cluster create mycluster --servers 1 --agents 2 -p "8080:30000@loadbalancer"
- k3d cluster delete -a (deleta todos os cluster)
- kubectl get pods
- kubctl get nodes
- kubectl get deployments
- kubectl get all
