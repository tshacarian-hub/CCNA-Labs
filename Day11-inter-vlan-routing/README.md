# CCNA Lab 11 — Inter-VLAN Routing

## Objective
Enable communication between VLANs using router-on-a-stick.

## Steps
1. Created VLANs
2. Configured trunk link
3. Configured router subinterfaces
4. Assigned default gateways
5. Tested connectivity

##Screenshot
<img width="730" height="735" alt="Trunk config" src="https://github.com/user-attachments/assets/f27c1dbb-ab1e-4d02-b060-cde8192bf643" />
<img width="716" height="727" alt="Router subinterface config" src="https://github.com/user-attachments/assets/aa10c6dc-7836-4d1e-a1ed-ee4652576a32" />
<img width="1772" height="800" alt="Successful inter-VLAN ping" src="https://github.com/user-attachments/assets/886a9bd5-fa68-4f5b-9079-e601498d5249" />
<img width="707" height="512" alt="Topology" src="https://github.com/user-attachments/assets/d157207b-e0bb-415c-9981-3dcbed563609" />
<img width="730" height="735" alt="Trunk config" src="https://github.com/user-attachments/assets/579b1fa9-02ce-45ec-b166-f7c557ea2d54" />
<img width="730" height="721" alt="VLAN config" src="https://github.com/user-attachments/assets/69605904-ccac-46cf-927c-f06066d2adbd" />

## Commands Used
encapsulation dot1Q
ip address
no shutdown

## Result
Devices in different VLANs successfully communicated.

## Troubleshooting

### Issue
Received error when creating subinterfaces:
<img width="720" height="742" alt="Subinterface error" src="https://github.com/user-attachments/assets/7d787a9a-66fc-4552-8d42-500c92a785df" />


%Invalid interface type and number

### Cause
Used incorrect interface name (fa0/0), but the router uses GigabitEthernet interfaces.

### Fix
Verified interfaces using:

show ip interface brief
<img width="720" height="722" alt="Solved error" src="https://github.com/user-attachments/assets/fd9fc434-f723-477a-bbe5-f3786e59e742" />

Then corrected configuration:

interface g0/0.10
encapsulation dot1Q 10
ip address 192.168.10.1 255.255.255.0

### Result
Subinterfaces configured successfully and inter-VLAN routing worked.
