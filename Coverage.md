---
title: Coverage
layout: page
---
# Coverage

MapleMesh's coverage is focused on Maple Valley and the surrounding towns: Covington, Hobart, Ravensdale, Black Diamond, but coverage may stretch into other areas as we grow.

## Maps
### Current
This is the coverage we expect to have active right now. None of this is guaranteed, but our tests show it at least broadly conforms to reality.

![Current Coverage](images/coverage/coverage-25-09-29.png)

## Process
Maps are created using [Radio Mobile for Windows](https://www.ve2dbe.com). To create ones in this style, use the following steps:
1. Configured all units correctly for their position, elevation, transceivers, antenna system parameters, and so on.
1. Overlay the InternetVirtualEarth map on the map with the *Operation* set to *Multiply*.
1. Repeat. This is the best way to get roads actually readable once you throw the coverage data on top.
1. Run your coverage for the node or nodes. 
  - Polar coverage is faster, but less precise. 
  - Cartesian coverage lets you combine multiple nodes' coverage as well as create Best Unit maps that differentiate between nodes' coverage instead of showing combined coverage.

---