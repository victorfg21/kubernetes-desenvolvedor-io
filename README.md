# Projeto do DevStore com Kubernetes

Este repositório contém um projeto voltado para estudos sobre Kubernetes, baseado no curso da plataforma Desenvolvedor.io.

Projeto desenvolvido durante o curso Dominando o Kubernetes onde é realizado o deploy de uma aplicação microserviços em ASP.NET Core com banco de dados Postgre e SQL Server utilizando o minikube para simular o ambiente do kubernetes.

## Objetivo

O projeto tem como objetivo fornecer uma base prática para a implantação e gerenciamento de aplicações em um cluster Kubernetes.

## Tecnologias Utilizadas

- Kubernetes
- Docker
- ASP.NET Core
- PostgreSql
- SqlServer
- RabbitMQ
- Minikube
- Helm
- YAML

## Requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- Docker
- Minikube ou um cluster Kubernetes
- Kubectl
- Helm

## Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/victorfg21/kubernetes-desenvolvedor-io.git
   cd kubernetes-desenvolvedor-io
   ```

2. **Inicie o Minikube (caso esteja utilizando):**
   ```bash
   minikube start
   ```

3. **Aplique os manifests Kubernetes:**
   ```bash
   kubectl apply -f manifests/
   ```

4. **Verifique os recursos implantados:**
   ```bash
   kubectl get all
   ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
