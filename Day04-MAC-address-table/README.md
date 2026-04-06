# CCNA Lab 04 — MAC Address Table Learning

## Objective
Demonstrate how a switch learns MAC addresses.

## Topology
PC0 → Switch → PC1

## Steps
1. Configured IPv4 addresses
2. Generated traffic using ping
3. Viewed MAC address table on switch

## Commands Used
show mac address-table
<img width="728" height="730" alt="Switch CLI" src="https://github.com/user-attachments/assets/7e50faa1-1555-4e9f-9c28-c72bc50ac3e5" />

clear mac address-table dynamic
<img width="742" height="483" alt="clear mac address-table dynamic" src="https://github.com/user-attachments/assets/c85de47f-0d78-4c52-a88f-2cd0eac0f65b" />

## Result
Switch dynamically learned MAC addresses for each connected device.
<img width="718" height="720" alt="MAC address clearing and relearning" src="https://github.com/user-attachments/assets/3c693b9c-8ce2-41c1-ac01-22d1d9212fbe" />
<img width="775" height="729" alt="Ping results" src="https://github.com/user-attachments/assets/17c9120e-b33c-4b6f-99f3-e2b5e54be77a" />
