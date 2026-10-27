# packet-tracer-lan-port-security
LAN design with Port Security and VLAN 1 management on Cisco Packet Tracer
# LAN Design & Port Security - Cisco Packet Tracer

## Overview
Star-topology LAN built in Cisco Packet Tracer with a 2960 switch and 5 PCs,
secured using Port Security and managed through VLAN 1.

## Topology
![Topology](topology.png)

## Network Details
| Item | Value |
|------|-------|
| Network | 10.10.10.0/24 |
| Switch | Cisco 2960-24TT |
| Devices | PC1 - PC5 |
| Cabling | Copper Straight-Through |
| Management IP | 10.10.10.100 (VLAN 1) |

## What I Implemented
- Port Security with Sticky MAC on access ports
- Troubleshooting a violation that caused err-disabled state
- Management IP on VLAN 1 (SVI)
- Connectivity testing with ping

## Key Commands
