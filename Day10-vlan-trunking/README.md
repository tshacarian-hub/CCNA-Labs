# CCNA Lab 10 — VLAN Trunking

## Objective
Extend VLANs across multiple switches using trunking.

## Topology
<img width="837" height="392" alt="Topology (2 switches)" src="https://github.com/user-attachments/assets/4deee856-6ced-41fc-89bc-9560fd79e699" />
## Steps
1. Created VLANs on both switches
<img width="707" height="733" alt="VLAN config" src="https://github.com/user-attachments/assets/c46603cd-b59d-4197-ac20-92c94eba8ca4" />
2. Assigned access ports
3. Configured trunk link
<img width="743" height="752" alt="Trunk config (show interfaces trunk)" src="https://github.com/user-attachments/assets/4c26f47e-1a57-4fe7-a371-9921282120b0" />
4. Tested connectivity
<img width="1449" height="842" alt="Successful cross-switch ping" src="https://github.com/user-attachments/assets/d2b7fdeb-ea4a-49f0-934e-825c4e51bf4d" />
<img width="1446" height="854" alt="Failed inter-VLAN ping" src="https://github.com/user-attachments/assets/4ed42331-1d84-4691-84f0-69dd58d002ad" />

## Commands Used
switchport mode trunk

show interfaces trunk

## Result
VLANs successfully extended across switches using trunking.
