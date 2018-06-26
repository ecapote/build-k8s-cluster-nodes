# build-k8s-cluster-nodes
Builds k8s enabled nodes to be used as controllers/nodes in a k8s cluster

This playbook will setup all the dependencies needed to setup a kubernetes controller and/or nodes. 

Requirements:
1. Setup a helper node with ansible, pip, git installed
2. ssh key access to all nodes.
