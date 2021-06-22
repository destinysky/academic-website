---
title: Implementation of Virtual Network Function Allocation with Diversity and
  Redundancy in Kubernetes
publication_types:
  - "1"
authors:
  - R. Kang
  - M. Zhu
  - F. He
  - T. Sato
  - and E. Oki
publication: IFIP Networking 2021
publication_short: IFIP Networking 2021
abstract: Diversity in network function virtualization is to use a group of thin
  replicas to provide the network services under the required processing
  ability. Redundancy is to provide a certain number of replicas against
  function failures and improve network reliability. Kubernetes is a system to
  deploy and manage virtual network functions automatically. Existing tools in
  Kubernetes do not provide a resource type to provide required functions
  jointly considering VNF diversity and redundancy. This paper designs and
  implements a custom resource and the corresponding controller in Kubernetes to
  manage the VNF diversity and redundancy jointly. The controller selects
  suitable replicas from a pool of replica templates to satisfy the required
  processing ability with the minimum required number of replicas and converts
  the backup functions to the primary functions when the primary functions
  cannot provide the required ability. Demonstration validates that the
  controller automatically manages the resources correctly, improves the
  resource utilization, and increases the number of acceptable requests.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
summary: >
  This paper designed and implemented a controller in Kubernetes. We introduced
  the structure and the components in the controller in details.
date: 2021-06-21T15:00:05.225Z
---
