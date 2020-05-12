# ml-microservice-kubernetes
[![CircleCI](https://circleci.com/gh/sushma-sri/ml-microservice-kubernetes.svg?style=svg)](https://app.circleci.com/pipelines/github/sushma-sri/ml-microservice-kubernetes)

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes-Specific Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create a Flask app in a Container
* Run via kubectl 
* You can choose to run one cluster locally with [Minikube](https://kubernetes.io/docs/tasks/tools/install-minikube/)

