# CCNA Lab 06 — ARP Analysis

## Objective
Understand how ARP resolves IP addresses to MAC addresses.

## Topology
PC0 → Switch → PC1

## Steps
1. Cleared ARP tables
2. Sent ping traffic
3. Observed ARP request and reply in simulation mode
4. Verified ARP table

## Commands Used
arp -a
arp -d
show mac address-table

## Key Concept
ARP uses broadcast to discover MAC addresses before communication.

## Result
Successful ARP resolution and ICMP communication.
