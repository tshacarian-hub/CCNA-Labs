# CCNA Lab 07 — Switch Forwarding Behavior

## Objective
Understand how switches forward traffic based on MAC address tables.

## Topology
3 PCs connected to a switch
<img width="876" height="726" alt="Topology (3 PCs + switch)" src="https://github.com/user-attachments/assets/4b1aaa51-4c40-4d38-965f-3f4f65c00323" />

## Steps
1. Cleared MAC address table
2. Sent traffic between devices
<img width="911" height="803" alt="First ping (flooding behavior)" src="https://github.com/user-attachments/assets/07dd392e-62cf-4465-8992-fd620303e558" />
<img width="913" height="832" alt="Second ping (unicast only)" src="https://github.com/user-attachments/assets/4c89cc4b-4429-4f3f-bc63-72cb3becabd9" />
3. Observed unknown unicast flooding
4. Observed unicast forwarding after learning
5. Observed ARP broadcast behavior
<img width="916" height="789" alt="ARP broadcast in simulation" src="https://github.com/user-attachments/assets/1e6c603a-838a-4d0f-9813-e30f1810485a" />

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
<img width="710" height="725" alt="MAC table before and after learning" src="https://github.com/user-attachments/assets/96c5607f-cc27-4acd-b2b5-90080a881d37" />
