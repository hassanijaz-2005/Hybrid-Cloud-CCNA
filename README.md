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
Switches: OnPremSwitch, SW2VPNTransit, SW3-Cloud-LAN
Connectivity: NAT1 provides internet access for StrongSwan and servers

Insert topology diagram here 


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
