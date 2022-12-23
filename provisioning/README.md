# Provisioning

The core idea behind the provisioning is to automate the process of creating an environment.

In our case, initially, we need a pipeline (github workflow) consisting of two stages:

- Create Resources - that uses terraform to create needed GCP resources. [More](./terraform.md)
- Install Kubeflow - that installs Kubeflow on an existing GKE cluster.

Possibly, we'll add more stages ;)

---

### Go back to [Docs](../)
