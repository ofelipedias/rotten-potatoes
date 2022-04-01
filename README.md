# rotten-potatoes

## Configuração

Utilizar o comando abaixo para criar o cluster:

`k3d cluster create kubedev-cluster --servers 3 --agents 3 -p "8080:30000@loadbalancer"`

Com o cluster criado execute o comando abaixo para fazer o deploy no cluster:

`kubectl apply -f deployment.yaml`

A imagem utilizada para fazer o deploy se encontra no registry.

https://hub.docker.com/repository/docker/felipedias/rotten-potatoes
