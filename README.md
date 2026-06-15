# CNRoutingAssignment

## Computer Networks - Router Configuration Assignment
**Student ID:** 39160  
**Module:** Computer Networks  

---

## Repository Contents

This repository contains three Cisco Packet Tracer files for the Computer Networks Routing Assignment.

---

## Task 1 - Basic Router Configuration
**File:** `Task1_BasicConfig_39160.pkt`

This task covers basic router configuration including setting the hostname to KandyNSBM_39160, configuring console password authentication using the password NSBM, and enabling console login security.

---

## Task 2 - Static Routing Configuration
**File:** `Task2_StaticRouting_39160.pkt`

This task involves configuring three routers (BusinessRouter, ComputingRouter, ScienceRouter) with IP addressing and static routes. Static routes were manually added to enable communication between three separate networks (192.168.1.0/24, 192.168.2.0/24, 192.168.3.0/24). Successful communication was verified using ping tests between all networks.

---

## Task 3 - Dynamic Routing Configuration
**File:** `Task3_DynamicRouting_39160.pkt`

This task covers dynamic routing using two protocols:

**Part A - RIP Routing:**  
Configured RIP version 2 on three routers (KandyNSBM, ColomboNSBM, GalleNSBM) to enable automatic route learning between networks 172.16.0.0/16 and 173.16.0.0/16.

**Part B - EIGRP Routing:**  
Replaced RIP with EIGRP (Autonomous System 100) on all three routers. EIGRP provided faster convergence and more efficient routing between all networks.

---

## Network Topology

| Task | Routers | Networks |
|------|---------|----------|
| Task 2 | BusinessRouter, ComputingRouter, ScienceRouter | 192.168.1.0/24, 192.168.2.0/24, 192.168.3.0/24 |
| Task 3 | KandyNSBM, ColomboNSBM, GalleNSBM | 172.16.0.0/16, 173.16.0.0/16 |
