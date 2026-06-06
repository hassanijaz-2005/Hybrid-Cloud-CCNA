# Hybrid-Cloud-CCNA
This repository contains a GNS3 lab demonstrating a hybrid cloud network. It includes Cisco routers and switches, Ubuntu servers for on-premises and cloud environments, and a StrongSwan VPN Gateway running in Docker. The lab shows basic IP addressing, static routing, and connectivity between on-prem and cloud networks.
Key features:
Router and switch configurations for LAN and cloud interconnection.
StrongSwan VPN Gateway for secure site-to-site connections.
Ubuntu servers with static IPs for on-prem and cloud.
Step-by-step topology and connection documentation.
Verification commands for testing connectivity and routing.

This project serves as a reference for designing, configuring, and testing hybrid cloud networks in GNS3.
IPsec Tunnel: Between Cisco Router and StrongSwan Gateway
Switches: 
1)SW1OnPremSwitch
2)SW2VPNTransit
3)SW3-Cloud-LAN
Connectivity: NAT1 provides internet access for StrongSwan and servers


<img width="1917" height="756" alt="Network Topology" src="https://github.com/user-attachments/assets/4025e69b-c74b-4562-bc10-33b9f54418e8" />

Setup Instructions
GNS3 VM Configuration: Install and configure the GNS3 VM.
Device Setup:
Add Cisco Router, Ubuntu Servers, StrongSwan Gateway, Switches.
Connect devices as per the topology.
Routing Configuration:
Configure static and dynamic routing on Cisco router.
Assign IP addresses to all interfaces.
IPsec Configuration:
Install StrongSwan on the gateway container.
Configure pre-shared key and tunnel parameters.
Connectivity Test: Ping across on-prem and cloud networks to verify tunnel functionality.
| Role                                           | Assigned To             | Responsibilities                                                                                                                                                                         |
| ---------------------------------------------- | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Project Lead + Network Architect**           | Muhammad Hassan Ijaz    | Design the network topology, create the GNS3 lab, configure routers, switches, and basic routing. Oversee the project execution and ensure connectivity between on-prem and cloud nodes. |
| **Security Engineer + Automation Lead**        | Muhammad Taufeeq Majeed | Configure StrongSwan IPsec, firewall rules, VPN, and security settings. Automate repetitive tasks using scripts, test connectivity, and ensure secure data flow.                         |
| **Testing / QA Engineer + Documentation Lead** | Shared by both          | Validate connectivity between all nodes, perform ping/traceroute tests. Document each step, commands used, screenshots, and project progress. Prepare README and GitHub updates.         |

