# homelab

Setup and fun times

I run a kubernetes cluster at home on a turing pi 2 raspberry pi cluster (hodgepodge of cm4 modules miraculously acquired over covid).

Mostly used for managing iot things, but also some SaaS apps I don't want to host everywhere. I'm new to this type of deployment. so any feedback is valued.

## Installation

Generally modeled after this
https://docs.turingpi.com/docs/turing-pi2-kubernetes

Setup on the turingpi, k3s, metalLB, argoCD, and storage

## Install Ingress

`kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/static/provider/cloud/deploy.yaml`
