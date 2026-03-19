# CCNA Lab 07 — Switch Forwarding Behavior

## Objective
Understand how switches forward traffic based on MAC address tables.

## Topology
3 PCs connected to a switch

## Steps
1. Cleared MAC address table
2. Sent traffic between devices
3. Observed unknown unicast flooding
4. Observed unicast forwarding after learning
5. Observed ARP broadcast behavior

## Commands Used
show mac address-table
clear mac address-table dynamic
arp -d

## Key Concepts
- Unicast
- Broadcast
- Unknown Unicast

## Result
Switch correctly learned MAC addresses and optimized forwarding.
