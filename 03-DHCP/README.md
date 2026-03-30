# DHCP Configuration

## Objective
To configure Dynamic Host Configuration Protocol (DHCP) in Cisco Packet Tracer for automatic IP address assignment to multiple PCs in a network.

## Description
This lab demonstrates how DHCP can be used to automatically assign IP addresses, subnet masks, default gateways, and DNS server addresses to client devices. Instead of manually configuring each PC, the DHCP server/router provides the required network settings dynamically.

## Devices Used
- 1 Router / DHCP Server
- 1 Switch
- Multiple PCs
- Copper straight-through cables

## Concepts Covered
- DHCP basics
- Automatic IP address assignment
- Default gateway configuration
- Network connectivity testing

## Network Details
- Network Address: `192.168.1.0/24`
- Default Gateway: `192.168.1.1`
- DNS Server: `8.8.8.8`
- DHCP Pool Name: `LAN_POOL`

## Steps Performed
1. Added one router, one switch, and multiple PCs in Packet Tracer.
2. Connected all PCs to the switch.
3. Configured the router interface with an IP address.
4. Created a DHCP pool on the router/server.
5. Assigned network details such as default gateway and DNS server.
6. Set all PCs to obtain IP addresses automatically.
7. Verified successful IP assignment and connectivity using `ping`.

## Verification
- PCs received IP addresses automatically
- DHCP pool assigned addresses correctly
- Successful ping between devices



## Result
All client PCs were able to obtain IP addresses dynamically and communicate successfully within the network.

## Conclusion
This lab helps in understanding how DHCP simplifies network management by automatically assigning IP addresses and reducing manual configuration errors.
