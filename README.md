SmartBranch 360 — Network Infrastructure Design
📌 Project Overview

SmartBranch 360 is a small-office network infrastructure project designed and configured using Cisco Packet Tracer. The network is designed to provide secure and organized connectivity by separating different types of users and devices into dedicated VLANs.

The project demonstrates practical concepts in computer networking, network segmentation, routing, switching, IPv4 addressing, and network troubleshooting.

🎯 Objectives
Design a functional small-office network infrastructure.
Segment network traffic using VLANs.
Configure inter-VLAN communication.
Implement router-on-a-stick routing.
Configure 802.1Q trunking between switches and router.
Assign IPv4 addresses and default gateways.
Test and troubleshoot network connectivity.
🏗️ Network Topology

The network consists of:

1 Cisco ISR4331 Router
2 Cisco Switches
1 Wireless Access Point
1 Server
8+ End Devices
Internet/Cloud connection
VLAN Configuration
VLAN	Name	Purpose
VLAN 10	EMPLOYEE	Employee devices
VLAN 20	GUEST	Guest devices
VLAN 30	SERVER	Server infrastructure
VLAN 40	MANAGEMENT	Network management
VLAN 99	UNUSED	Unused ports
🌐 Networking Concepts Implemented
VLAN Segmentation

Separate VLANs were created for employees, guests, servers, and management devices to improve network organization and isolation.

802.1Q Trunking

Trunk links were configured to carry traffic from multiple VLANs between network devices.

Router-on-a-Stick

Router subinterfaces were configured to enable communication between different VLANs using a single physical router interface.

IPv4 Addressing

Devices were assigned IPv4 addresses, subnet masks, and default gateways according to their respective VLAN networks.

🔧 Troubleshooting

Network connectivity was tested using ping between devices.

During testing, connectivity issues were identified and resolved by checking:

VLAN assignments
Switch port configurations
Trunk configuration
Router subinterfaces
IP addresses
Default gateways

Successful ping tests were used to verify network connectivity after configuration changes.

🛠️ Tools & Technologies
Cisco Packet Tracer
Cisco ISR4331 Router
Cisco Switches
IPv4
VLANs
802.1Q
Inter-VLAN Routing
Router-on-a-Stick
TCP/IP Networking
📂 Project Files
SmartBranch360.pkt — Cisco Packet Tracer network project
screenshots/ — Network topology and configuration screenshots
📸 Screenshots
Network Topology

Add your Packet Tracer topology screenshot here.

VLAN Configuration

Add a screenshot showing the VLAN configuration here.

Connectivity Testing

Add a screenshot showing successful ping/ connectivity testing here.

📚 Key Learning Outcomes

Through this project, I gained practical experience with:

Designing network topologies
VLAN configuration and network segmentation
Switch and router configuration
802.1Q trunking
Inter-VLAN routing
IPv4 addressing
Network connectivity testing
Troubleshooting network configuration issues
👩‍💻 Author

Srinija Thurpati

Computer Science & Engineering Student
Malla Reddy Engineering College for Women, Hyderabad
