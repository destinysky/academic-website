---
title: Robust Virtual Network Function Allocation in Service Function Chains
  with Uncertain Availability Schedule
subtitle: ""
publication_types:
  - "2"
authors:
  - R. Kang
  - F. He
  - and E. Oki
publication_short: IEEE TNSM
abstract: The availability schedule provides information on whether each network
  node is available at each time slot. The service interruptions caused by node
  unavailability marked in availability schedule can be suppressed if the
  functions are allocated according to the availability schedule. However, the
  given availability schedule may have gaps with the actual one and influence
  the VNF allocation. This paper proposes a robust optimization model to
  allocate virtual network functions (VNFs) in service function chains (SFCs)
  for time slots in sequence aiming to maximize the continuous available time of
  SFCs in a network with uncertain availability schedules by suppressing the
  interruptions caused by node unavailability marked in availability schedule
  and function reallocation. We formulate the problem as a mixed integer linear
  programming (MILP) problem over the given uncertainty set of the start time
  slot and period of unavailability on each node in the availability schedule.
  For solving the model in a practical time in a relative large size of network,
  we develop a heuristic algorithm. The numerical results show that the proposed
  model outperforms the baseline models under different levels of robustness in
  terms of the worst-case minimum number of the longest continuous available
  time slot in each SFC. The heuristic algorithm reduces the computation time
  with limited performance loss compared with the MILP approach. In the
  discussion, we introduce a constraint condition for the maintenance ability,
  which reduces the size of uncertainty set, and an extension for supporting
  more than one unavailability periods in the availability schedule on each
  node.
draft: false
featured: false
projects: []
slides: ""
url_pdf: ""
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
author_notes: []
doi: ""
publication: IEEE Transactions on Network and Service Management
tags: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2021-04-28T11:41:22.772Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
