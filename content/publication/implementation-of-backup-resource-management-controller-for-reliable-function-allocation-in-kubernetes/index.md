---
title: Implementation of Backup Resource Management Controller for Reliable
  Function Allocation in Kubernetes
publication_types:
  - "1"
authors:
  - M. Zhu
  - R. Kang
  - F. He
  - and E. Oki
publication: 7th IEEE International Conference on Network Softwarization (NetSoft 2021)
publication_short: NetSoft 2021
abstract: Resource allocation and management is a key role in network function
  virtualization to improve the reliability of network services. Kubernetes is a
  system to deploy and manage the virtual network functions automatically.
  Existing tools in Kubernetes does not provide a resource type to define the
  backup Pods. It does not provide automatic resource management based on the
  user requests for the backup Pods, either. This paper designs and implements a
  custom resource and the corresponding controller in Kubernetes to manage the
  primary and backup resources of network functions. The custom resource is a
  set of Pods with different types, which includes primary, hot backup, and cold
  backup Pods. The controller manages the set of Pods and maintains the current
  state of the different types of Pods to keep the current state consistent with
  the desired state of each type of Pod. Demonstration validates that the
  controller automatically manage the primary and backups resources correctly.
draft: false
featured: true
image:
  filename: ""
  focal_point: ""
  preview_only: false
summary: "This paper designs and implements a custom resource and the
  corresponding controller in Kubernetes to manage the primary and backup
  resources of network functions. "
date: 2021-07-01T12:55:00.000Z
---
