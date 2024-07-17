# mx-chain-observing-squad-helm

Helm chart used to deploy an observing squad on Kubernetes.

## Prerequisites
1. Kubernetes cluster
2. [Helm](https://helm.sh/)
3. [Kubectl](https://kubernetes.io/docs/reference/kubectl/)
4. [git](https://git-scm.com/)

## Getting started
1. Git clone the repository
```
$ git clone https://github.com/cristure/mx-chain-observing-squad-helm
```

2. Make sure that you can actually connect to your K8s cluster with kubectl
```
$ kubectl get pods
```

3. Install the chart
```
# helm install observing squad mx-chain-observing-squad-helm
```

Please note that, if not specified, all the resources will be deployed in the `default` namespace. One can tweak 
configurations in the `values.yaml`