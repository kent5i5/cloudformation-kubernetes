Structure image:
https://www.lucidchart.com/documents/view/73ab5ccb-9695-43e9-b4a9-89556feb0ca0/0_0


This is a udacity project

Goal:
Pick AWS Kubernetes as a Service, or build your own Kubernetes cluster.
Use Ansible or CloudFormation to build your “infrastructure”; i.e., the Kubernetes Cluster.
It should create the EC2 instances (if you are building your own), set the correct networking settings, and deploy software to these instances.
As a final step, the Kubernetes cluster will need to be initialized. The Kubernetes cluster initialization can either be done by hand, or with Ansible/Cloudformation at the student’s discretion.

This script will create 2 instance of EC2 instances and will scale up if necessary.

EC2 Instances Installations:
docker
kubernetes - kubectl
minikube