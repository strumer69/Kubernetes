# Kubernetes
## why to use Kubernetes:
* https://kubernetes.io/docs/concepts/overview/#why-you-need-kubernetes-and-what-can-it-do
* You tell Kubernetes how much CPU and memory (RAM) each container needs.
* Kubernetes lets you store and manage sensitive information, such as passwords, OAuth tokens, and SSH keys.
## Kubernetes components:
* https://kubernetes.io/docs/concepts/overview/components/
### 1-Control Plane Components :
* Manage the overall state of the cluster:

#### kube-apiserver
* The core component server that exposes the Kubernetes HTTP API.
#### etcd
* Consistent and highly-available key value store for all API server data.
  
#### kube-scheduler
* Looks for Pods not yet bound to a node, and assigns each Pod to a suitable node.
* **POD**: --> Pods are the **smallest** deployable units of computing that you can create and manage in Kubernetes.
* A Pod (as in a pod of whales or pea pod) is a group of one or more containers, with shared storage and network resources, and a specification for how to run the containers
#### kube-controller-manager
  * Runs controllers to implement Kubernetes API behavior.
#### cloud-controller-manager (optional)
Integrates with underlying cloud provider(s).

### 2-Node Components 
* Run on every node, maintaining running pods and providing the Kubernetes runtime environment:

#### kubelet
* Ensures that Pods are running, including their containers.
#### kube-proxy (optional)
* Maintains network rules on nodes to implement Services.
#### Container runtime
* Software responsible for running containers. Read Container Runtimes to learn more.
### 3-Addons:
* Addons extend the functionality of Kubernetes. A few important examples include:

#### DNS
* For cluster-wide DNS resolution.

#### WEB UI
* For cluster management via a web interface.
#### Container Resource Monitoring
  * For collecting and storing container metrics.
#### Cluster-level Logging
* For saving container logs to a central log store.
*  ---------------------------------------------------------------------
*  next step --> try kubernets
*  https://kubernetes.io/docs/home/
*  helle MINIKUBE:
*  https://kubernetes.io/docs/tutorials/hello-minikube/
*  





