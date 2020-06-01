# `kaas`

"kaas": noun
   1. Multi-tenant Multi-Cluster Kubernetes-as-a-Service
   2. *(dutch)* "Cheese"

**This repository is a WIP, i'll plan to start working on this sometime in the future, using products from [multi-tenancy](https://github.com/kubernetes-sigs/multi-tenancy) and [submariner](https://submariner.io/) to make this happen**

# The Goal

Provide a simple dashboard admin GUI (with CLI feature pairing) for sysadmins/devops to provision and provide virtual clusters to internal teams and business customers alike.

Define resource pools (Loadbalancer IPs, ingress subdomain patterns, storage classes, etc.) and limits to be used by Tenant clusters in an intuitive and easy way (think DigitalOcean dashboard).

Provide mission-agnostic functions/features that can serve: 
- professional usecases (commercial & internal)
- hobbyist collaberative usecases (collaberative clustering, providing compute resources from a local homelab cluster to a wider community, etc.)
- conventional abstract usecases (seperating a "personal" and "work" kubernetes cluster while using the same hardware)
