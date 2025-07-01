# Secure IPSec-over-MPLS Enterprise Branch Connectivity

This project is based on my MSc research in Computer Networks and Security at the University of Staffordshire. It demonstrates a secure and resilient enterprise network architecture that connects a remote branch office to a headquarters site using **MPLS Layer 3 VPN**, overlaid with **IPSec encryption** to protect data across an ISP core network.


---

## 🧠 Objectives

- Deploy an IPSec tunnel across an MPLS Layer 3 VPN architecture
- Simulate a real-world ISP CE/PE design with Cisco routers and Juniper SRX firewalls
- Implement dynamic routing using OSPF and MP-BGP
- Demonstrate how VRFs and GRE tunnels can be used for path isolation
- Validate connectivity scenarios with test outputs

---

## 🛠️ Technologies & Tools Used

| Category        | Details                                  |
|-----------------|------------------------------------------|
| Routing         | OSPF, MP-BGP, VRF                        |
| VPN             | IPSec (Tunnel Mode, IKEv2)               |
| Vendors         | Cisco IOS, Juniper SRX                   |
| Virtualisation  | VMware Workstation, EVE-NG               |
| Lab Simulation  | EVE-NG Emulator                          |
| Security        | ACLs, Firewall Policies, IPSec Tunnels   |
| Tools           | ping, traceroute, CLI-based testing      |

---

## 🔧 Topology Overview

The lab simulates an enterprise head office and a remote branch, connected via an ISP MPLS network. IPSec tunnels provide secure encrypted communication between the two sites.

📍 _Topology Diagram:_

![Network Topology](./LAB_TOPOLOGY.png)



