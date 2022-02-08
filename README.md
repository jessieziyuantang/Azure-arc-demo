# Calicocloud configuration sample for Azure Arc enabled Kubernetes 

This repository contains sample Kubernetes manifest files for calico networkpolicy that can be deployed using GitOps to an Azure Arc enabled Kubernetes cluster.

## Contents

| File/folder       | Description                                |
|-------------------|--------------------------------------------|
| `README.md`       | This README file. |
| `cluster-apps`    | Contains an example application that should be deployed to every cluster. |
| `namespaces`      | Contains three namespace resources to provision on an attached cluster. |

| `CODE_OF_CONDUCT.md` | Microsoft code of conduct. |
| `LICENSE`         | The license for the sample. |

## Prerequisites

One or more Kubernetes clusters are [connected to Azure Arc](https://docs.microsoft.com/en-in/azure/azure-arc/kubernetes/connect-cluster) using the `connectedk8s` Azure CLI extension.


It is designed for demoing Azure Arc for Kubernetes GitOps flow included in the ["Azure Arc Jumpstart GitHub repository"](https://github.com/likamrat/azure_arc/) but can really be used for other demo purposes easily. 

![](img/hello_arc.png)

## Credit

This repository and the "Hello Arc" application in it were forked from the great work done by Paul Bouwer as part of his ["Hello Kubernetes" GitHub repository](https://github.com/paulbouwer/hello-kubernetes) and all credits for the building blocks goes to him. 

Please refer to the repository for detailed instructions on how to build your on Docker image and deploy it. 

## Docker Hub

The container for this "Hello Arc" application can be found on [Docker Hub](https://hub.docker.com/r/liorkamrat/hello-arc). 

## Contributing

Before contributing code, please see the [CONTRIBUTING](CONTRIBUTING.md) guide.

Issues, PRs and Feature Request have their own templates. Please fill out the whole template.