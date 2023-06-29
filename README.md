# rancher-cluster-templates

Rancher Cluster Templates to provision RKE2 Kubernetes clusters

## How to Use with Fleet

* Go to the Continuous Delivery menu in Rancher
* Add a new Git Repository in the `fleet-local` workspace with the following:
```
- Repository URL: https://github.com/bloriot/rancher-cluster-templates.git
- Branch Name: fleet-dev
- Paths: charts/rancher-aws-cluster-template
```
