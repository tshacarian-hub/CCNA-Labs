# CCNA Lab 09 — VLAN Configuration

## Objective
Create and configure VLANs to segment a network.

## VLANs
- VLAN 10 (Sales)
- VLAN 20 (IT)

## Steps
1. Created VLANs
<img width="711" height="727" alt="show vlan brief" src="https://github.com/user-attachments/assets/cbd7f167-c3f1-4a6f-8cd0-6a1dcb000cff" />
2. Assigned switch ports
<img width="714" height="730" alt="VLAN configuration (CLI)" src="https://github.com/user-attachments/assets/4d8e96c4-c3a3-434c-9c85-2e48292b3d26" />
3. Configured IP addressing
4. Tested connectivity
<img width="885" height="778" alt="Successful ping (same VLAN)" src="https://github.com/user-attachments/assets/f9acf3f6-7a0a-4be8-8ea9-6afae3d3c4f9" />
<img width="1482" height="786" alt="Failed ping (different VLAN)" src="https://github.com/user-attachments/assets/937a3aeb-4723-41fd-8e45-635f8e4aae1e" />

## Commands Used
vlan 10
vlan 20
switchport access vlan
show vlan brief

## Result
Devices in same VLAN communicate successfully.  
Devices in different VLANs cannot communicate without routing.
