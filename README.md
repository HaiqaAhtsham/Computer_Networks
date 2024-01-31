# Network Design Project
## Overview
This network design project involves creating a comprehensive infrastructure based on a provided layout with minimal technical documentation. The aim is to efficiently configure the network, implement various protocols, and ensure secure and reliable communication among different components.

# Steps to Configure

## IP Address Assignment:
Retrieve the IP addresses from the attached "IP address" file.
Identify network addresses and allocate them accordingly.
## VLSM Configuration:
Determine the number of required hosts per subnet from the given file.
Implement Variable Length Subnet Masking (VLSM) to optimize IP address usage for each labeled group.
## Routing Protocols:
Utilize OSPF with Area 1 in the second block, RIP in the third block, and OSPF with Area 0 in the last block.
Enable redistribution on Router8 and Router21 to interconnect OSPF with OSPF and OSPF with RIP.
## DHCP Configuration:
Assign IP addresses from the "DHCP Server" to hosts in OSPF Area 1 and RIP.
Assign IP addresses from "DHCP Server for VLAN's" to hosts in OSPF Area 0.
## EIGRP Configuration:
Implement EIGRP in the first block for efficient routing.
Enable redistribution on Router5 and Router8 to connect EIGRP with OSPF.
## NAT Implementation:
Apply Network Address Translation (NAT) on the router with Network G.
Utilize the provided public IP address for NAT implementation.
## VLAN Configuration:
Create VLANs as specified in the scenario.
Use VTP, designating the 3560 switch as the server and others as clients. Ensure the light blue-shaded switch does not copy any VLAN.
## Inter-VLAN Communication:
Facilitate communication between hosts within the same VLAN.
Enable Inter-VLAN communication specifically between VLAN 20 and VLAN 40.
## Security Measures:
Implement IP security protocols between every router in the network.
## VLAN Routing:
Utilize router-on-stick technique for VLAN routing.
## Address Table:
Provide a comprehensive address table for all IP configurations in the network topology.
## Note
This configuration aims to create a robust, scalable, and secure network infrastructure based on the given specifications. Following these steps should result in a functional network environment.
## snapshots for better understanding
 ## Topology :
 ![image](https://github.com/HaiqaAhtsham/Computer_Networks/assets/138617805/d5380e8a-111c-4b04-811d-79d1b9402f4c)







