# Commands to start k3s cluster

- `curl -sfL https://get.k3s.io | INSTALL_K3S_EXEC="--disable=traefik" sh -`
- `sudo cat /etc/rancher/k3s/k3s.yaml`
- `export KUBECONFIG=/etc/rancher/k3s/k3s.yaml`

# Commands to spin up application

- `kubectl apply -f` all files
- `minikube tunnel`
