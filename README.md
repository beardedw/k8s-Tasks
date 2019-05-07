# k8s-Tasks

https://kubernetes.io/docs/tasks


https://kubernetes.io/docs/tasks


![content00](_image/content00.png)


@[TOC]

<!-- TOC -->autoauto- [k8s-Tasks](#k8s-tasks)auto    - [Install Tools](#install-tools)auto    - [install-kubectl](#install-kubectl)auto        - [Linux install](#linux-install)auto        - [Configuration](#configuration)auto        - [Completion](#completion)auto    - [install-minikube](#install-minikube)auto    - [configure-pod-container](#configure-pod-container)autoauto<!-- /TOC -->



## Install Tools
## install-kubectl

### Linux install

```
sudo mv ./kubectl /usr/local/bin/kubectl

kubectl version

```

###  Configuration


```
mkdir ~/.kube

touch ~/.kube/config


kubectl cluster-info

kubectl cluster-info dump

```


###  Completion

```
1. install bash-completion

apt install bash-completion


2. install kubectl completion

source <(kubectl completion bash)

或者 

echo "source <(kubectl completion bash)" >> ~/.bashrc

3.alias k as kubectl

alias k=kubectl
complete -F __start_kubectl k


```



## install-minikube

```
minikube start
```

## configure-pod-container



