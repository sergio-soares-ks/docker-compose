Para Instalação do Rancher/Server Local é necessários installar o minikube e o Kubernets

Instalação do Minikube Linux Ubuntu
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube && rm minikube-linux-amd64

comandos para verificar se tudo esta correto.
minikube start

kubectl get po -A


Instalação do Kubernets 
https://kubernetes.io/pt-br/docs/setup/
