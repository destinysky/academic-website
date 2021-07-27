---
title: Virtual Network Function Allocation in Service Function Chains Using
  Backups with Availability Schedule
publication_types:
  - "2"
authors:
  - R. Kang
  - F. He
  - and E. Oki
doi: 10.1109/TNSM.2021.3096254
publication: IEEE Transactions on Network and Service Management
publication_short: IEEE TNSM
abstract: A suitable virtual network function (VNF) placement considering a node
  availability schedule extends service continuous serviceable time by
  suppressing service interruptions caused by function reallocation and node
  unavailabilities. However, function placement cannot avoid service
  interruptions caused by node unavailabilities. This paper proposes a primary
  and backup VNF placement model to avoid service interruptions caused by node
  unavailabilities by using backup functions. The considered backup functions
  have a period of startup time for preparation before they can be used and the
  number of them is limited. The proposed model is formulated as an integer
  linear programming problem to place the primary and backup VNFs based on the
  availability schedule at continuous time slots. We aim to maximize the minimum
  number of continuously available time slots in all service function chains
  (SFCs) over the deterministic availability schedule. We obverse that the
  proposed model considering the limited number of backup functions outperforms
  baseline models in terms of the minimum number of longest continuous available
  time slots in all SFCs. We introduce an algorithm to estimate the number of
  key unavailabilities at each time slot, which can find the unavailable nodes
  which are the bottlenecks to increase the service continuous available time at
  each time slot.
draft: false
featured: true
image:
  filename: ""
  focal_point: ""
  preview_only: false
summary: The proposed model is formulated as an integer linear programming
  problem to place the primary and backup VNFs based on the availability
  schedule at continuous time slots. We aim to maximize the minimum number of
  continuously available time slots in all service function chains (SFCs) over
  the deterministic availability schedule.
date: 2021-07-27T03:16:23.849Z
---
