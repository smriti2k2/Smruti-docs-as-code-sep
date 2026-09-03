- [Getting started](#getting-started)
  - [Before you begin](#before-you-begin)
## Getting started 
If you are new to the BMC AMI Platform product, read and perform the getting started tasks to learn how to simplify daily operations, improve knowledge retention, and support both experienced and new mainframe professionals using the **BMC AMI Platform** product. 

### Before you begin
The BMC AMI Platform runs on Kubernetes‑based container orchestration, with Red Hat OpenShift providing the enterprise Kubernetes distribution. Kubernetes provides the core control plane and worker node architecture required to schedule, execute, scale, and self‑heal containerized workloads. Control‑plane components, including the **API server**, scheduler, controller manager, and etcd datastore, manage cluster state and orchestration logic, while worker nodes host platform and application pods via the kubelet and container runtime. 

 Version 2.2.00 introduces several key enhancements:

* **User Management**: Authentication using z/OSMF mainframe credentials for secure access.
* **Observability**: Advanced monitoring and diagnostic tools for improved system visibility.
* **Deployment Orchestration**: Kubernetes‑based orchestration with native Red Hat OpenShift support, providing scalable, secure, and streamlined application deployments.
* **AI Integration**: Includes the BMC AMI Assistant chat interface and AI-driven services to assist with operational tasks.

  These features aim to provide a more automated and integrated mainframe ecosystem without altering existing core functionality.

| Core objective | Details |
|------|------|
| Deployment | <ul><li>Declares the desired application version.</li><li>Specifies the pod count.</li><li>Defines the rollback strategy.</li></ul> |
| ReplicaSet | <ul><li>Maintains the required number of identical pods.</li><li>Replaces failed or deleted pods automatically.</li></ul> |