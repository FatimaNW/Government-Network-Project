# Government-Network-Project
This project presents a comprehensive network scenario designed for a government setup, implemented using eNSP (Enterprise Network Simulation Platform). The network encompasses a central cloud system, seven departmental routers, DHCP and FTP servers, and various switches connecting departmental devices. The primary focus is on implementing key network technologies to ensure seamless connectivity and robust security across multiple government divisions. The following technologies were implemented to ensure optimal performance and security:

* Subnetting
* Telnet
* Access Control Lists (ACL) 
* Link Aggregation Control Protocol (LACP)
* Static Routing
* Dynamic Routing — RIP (Routing Information Protocol)
* Spanning Tree Protocol (STP)
* Variable Length Subnet Masking (VLSM)
* Virtual Local Area Network (VLAN)
* Dynamic Host Configuration Protocol (DHCP)
* File Transfer Protocol (FTP)

## Implemented Technologies

### Telnet
Telnet is configured for remote management and configuration of routers.

### Access Control Lists
ACL is applied on the AR2220 router (labeled AR1) to permit and restrict access from specific IP addresses.

### Link Aggregation Control Protocol (LACP)
An Eth-Trunk is configured in LACP mode between switches LSW10 and LSW11.

### Static Routing
Static routes are configured in the Transportation Division using routers: R9, R10, R11, R13, and R21.

### Dynamic Routing — RIP
RIP version 2 is enabled on all routers, allowing automatic exchange of routing information for directly connected networks.

### Spanning Tree Protocol
STP is configured in the Labour and Employment Division using switches LSW4, LSW8, LSW9, LSW10, and LSW11 to prevent network loops.

### Variable Length Subnet Masking
VLSM is used throughout the design to efficiently allocate IP addresses based on departmental requirements.

### Virtual Local Area Network
Inter-VLAN routing is implemented using 'Router-on-a-Stick' in the Home Affairs and Foreign Affairs Divisions to allow communication between VLAN 10 and VLAN 20 via router R5.

### Dynamic Host Configuration Protocol
Router R6 is configured as a DHCP server, while R8 acts as a DHCP relay agent.

### File Transfer Protocol (FTP)
Router R5 hosts the FTP service to enable file sharing between departments.

