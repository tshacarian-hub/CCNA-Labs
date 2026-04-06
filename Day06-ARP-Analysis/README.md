# CCNA Lab 06 — ARP Analysis

## Objective
Understand how ARP resolves IP addresses to MAC addresses.

## Topology
PC0 → Switch → PC1
<img width="409" height="578" alt="Topology" src="https://github.com/user-attachments/assets/50146a91-42aa-4690-af61-c5ed3e01d5a7" />

## Steps
1. Cleared ARP tables
2. Sent ping traffic
<img width="718" height="739" alt="Successful ping" src="https://github.com/user-attachments/assets/4f4705ed-745c-428d-9bde-97cd12326e75" />
4. Observed ARP request and reply in simulation mode
<img width="1072" height="774" alt="Simulation showing ARP reply" src="https://github.com/user-attachments/assets/8ad4aa53-a190-448d-bd85-1a3f8620f497" />
<img width="1566" height="770" alt="Simulation mode showing ARP request" src="https://github.com/user-attachments/assets/9d1dec7d-f302-4e5b-b9e9-edc8b147fcdd" />
6. Verified ARP table
<img width="713" height="734" alt="PC0 ARP table (arp -a)" src="https://github.com/user-attachments/assets/966eefd7-6f96-414d-b8ff-5f4fd29b0f76" />

## Commands Used
arp -a
arp -d
show mac address-table
<img width="703" height="714" alt="show mac address-table" src="https://github.com/user-attachments/assets/5ace69d6-8b34-4f46-99e5-c98d4bd196d2" />

## Key Concept
ARP uses broadcast to discover MAC addresses before communication.

## Result
Successful ARP resolution and ICMP communication.
