---
title: Design of Scheduler Plugins for Reliable Function Allocation in Kubernetes
publication_types:
  - "1"
authors:
  - R. Kang
  - M. Zhu
  - F. He
  - T. Sato
  - and E. Oki
doi: 10.1109/DRCN51631.2021.9477366
publication: 17th International Conference on the Design of Reliable Communication Networks
publication_short: DRCN 2021
abstract: The reliability of virtual network can be increased by allocating
  virtual network functions (VNF) to suitable locations. The VNF placement
  problems are formulated as optimization models with different objectives. The
  models are solved by optimization software and heuristic algorithms. The
  allocation results obtained by the models are used to allocate the VNFs to
  nodes. Since different users have different objectives, it is necessary to
  allocate different groups of VNFs by using different models. Existing tools
  did not provide a method to connect multiple optimization models with
  Kubernetes. We implement function scheduler plugins cooperating with multiple
  reliable function allocation models in Kubernetes, which is a system for
  automating deployment, scaling, and management of containerized applications.
  Demonstration validates that the plugins allocate functions by using the
  allocation results obtained by the model automatically and run service
  functions correctly.
draft: false
featured: true
image:
  filename: ""
  focal_point: ""
  preview_only: false
summary: We implement function scheduler plugins cooperating with multiple
  reliable function allocation models in Kubernetes, which is a system for
  automating deployment, scaling, and management of containerized applications.
date: 2021-04-22T13:00:00.000Z
---
