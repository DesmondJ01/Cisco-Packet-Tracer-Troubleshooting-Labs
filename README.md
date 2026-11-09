# Cisco-Packet-Tracer-Troubleshooting-Labs
This repository contains Troubleshootings labs from packet tracer. Ranging from large to smaller networks there will be read me's containg information of how I investigated the issue and how I resolve them with Youtube link included in read me. 

# Hospital Enterprise Network Lab – Cisco Packet Tracer

## Project Overview

This repository documents the ongoing development of a simulated hospital enterprise network built in Cisco Packet Tracer. The goal is to design, configure, and troubleshoot a multi-floor network environment using enterprise networking concepts.

## Current Progress

Currently developing the network infrastructure, including access switches, Layer 3 distribution, VLAN segmentation, inter-VLAN routing, and centralized network services.

### Troubleshooting Exercise: DHCP Connectivity

During development, I encountered a DHCP connectivity issue affecting devices on Floor 1, while Floor 2 devices continued to operate normally.

**Troubleshooting process:**
- Investigated VLAN assignments and trunk configurations.
- Reviewed EtherChannel configurations using LACP.
- Examined Spanning Tree Protocol (STP) forwarding and blocking states.
- Verified DHCP relay configuration.
- Identified an inconsistent allowed-VLAN configuration across redundant EtherChannel links.

**Technologies Used:**
- Cisco Packet Tracer
- VLANs and 802.1Q Trunking
- Inter-VLAN Routing
- DHCP and DHCP Relay
- EtherChannel (LACP)
- Spanning Tree Protocol (STP)
- Layer 2/Layer 3 Troubleshooting

## Future Development

- Expand the multi-floor network topology.
- Implement additional redundancy and routing.
- Integrate additional network services.
- Continue documenting configuration and troubleshooting exercises.

## Lab Demonstrations

https://youtu.be/AU2jQlS-YGc
