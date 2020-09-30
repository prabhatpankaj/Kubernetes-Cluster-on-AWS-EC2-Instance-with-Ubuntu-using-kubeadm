# Kubernetes-Cluster-on-AWS-EC2-Instance-with-Ubuntu-using-kubeadm

In this Lab, we will see how to set up a Kubernetes cluster with 2 Worker Nodes and 1 Master Node on Ubuntu 18.04 LTS Servers. We will use the "kubeadm" tool to set up the cluster. Kubeadm is a tool built to provide "kubeadm init" and "kubeadm join" for creating Kubernetes clusters. Before we proceed with the creation of the cluster let's understand a few terms in brief.

* Docker:\
Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. With Docker, you can manage your infrastructure in the same ways you manage your applications. 

* Image:\
An image is a read-only template with instructions for creating a Docker container. Often, an image is based on another image, with some additional customization

* Container:\
A container is a runnable instance of an image. You can create, start, stop, move, or delete a container using the Docker API or CLI. You can connect a container to one or more networks, attach storage to it, or even create a new image based on its current state.

* Kubernetes:\
Kubernetes is an open-source container-orchestration system for automating application deployment, scaling, and management.

* Nodes:\
A node represents a single machine in the cluster.

* Pods:\
A is a group of containers that are deployed together on the same host. It is the basic execution unit of a Kubernetes application.

* Deployments:\
A Deployment runs multiple replicas of your application and automatically replaces any instances that fail or become unresponsive. It provides declarative updates for Pods and ReplicaSets.

* Replica Set:\
It ensures how many replicas of a pod should be running. It can be considered as a replacement for the replication controller.

* Replication Controller:\
It is a supervisor for long-running pods. It will launch a specified number of pods called replicas and makes sure that they keep running all the time.

* Service:\
It is an abstraction that defines a logical set of Pods and a policy by which to access them.

* API Server, etcd,  Controller Manager &  Scheduler, are the components of the Master and  Docker,  Kubelet Service & Kubernetes Proxy Service are the components of Worker Node.

