Features of cloud front

Features of route 53

EKS Etcd is fully managed

* Can get manual and automatic upgrades of kubernetes version

* Get master and node upgrades are taken care of based on the number of pods on the cluster

* Cloud watch, cloudtrail, VPC networking integrations with EKS

* Steps: 1. Create EKS,
                       2. provision worker nodes
                       3.  Launch add ons
                       4. Launch worker nodes
Creating EKS what goes behind the Scenes:

* EKs spins 3 masters per cluster

* 1 highly available etcd

* Master and etcd are not colocated

EKS imposes rules and limited customization
