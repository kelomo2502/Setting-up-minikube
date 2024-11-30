# Setting-up-minikube

This project serves as a practical guide for beginners, offering step-by-step instructions for installing and configuring Minikube, a lightweight Kubernetes implementation, on various operating systems.

## Installation

- Windows
  `choco install minikube`
  `minikube start --driver=docker`
- Linux
  `sudo apt-get update`
  `curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube_latest_amd64.deb`
  `minikube start --driver=docker`
  `sudo snap install kubectl --classic`
- MacOs
  `curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-darwin-amd64`
  `sudo install minikube-darwin-amd64 /usr/local/bin/minikube`
  `minikube start --driver=docker`

