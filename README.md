# rancher-cluster-templates

Rancher Cluster Templates to provision RKE2 Kubernetes clusters

## How to Use

* Go to the Apps Marketplace in the `local` cluster in Rancher
* Add a new Git Repository to the Git Repo URL `https://github.com/bloriot/rancher-cluster-templates.git` without authentication
* In order to use a template as part of continuous delivery/GitOps, the cluster template needs to be deployed in the `fleet-local` namespace of the local cluster.
