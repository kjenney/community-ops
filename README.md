# Community Operations
[![kubernetes-cluster-01:deploy](https://img.shields.io/github/workflow/status/zufardhiyaulhaq/community-ops/kubernetes-cluster-01:master?label=kubernetes-cluster-01)](https://github.com/zufardhiyaulhaq/community-ops/actions/workflows/kubernetes-cluster-01:master.yaml) [![kubernetes-cluster-02:deploy](https://img.shields.io/github/workflow/status/zufardhiyaulhaq/community-ops/kubernetes-cluster-02:master?label=kubernetes-cluster-02)](https://github.com/zufardhiyaulhaq/community-ops/actions/workflows/kubernetes-cluster-02:master.yaml) [![GitHub issues](https://img.shields.io/github/issues/zufardhiyaulhaq/community-ops)](https://github.com/zufardhiyaulhaq/community-ops/issues) [![GitHub pull requests](https://img.shields.io/github/issues-pr/zufardhiyaulhaq/community-ops)](https://github.com/zufardhiyaulhaq/community-ops/pulls)

GitOps pattern for Kubernetes using ArgoCD, sealed-secrets, Helmfile, Kustomize, and python scripts. Implemented in my Kubernetes clusters. 

# Provision a Kubernetes cluster

We're using `cprov` - a Python module to provision EKS clusters

```
pip install cprov
cprov do eks
```
