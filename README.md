Project Title: Hybrid Cloud Network with IPsec
Description

This project demonstrates a hybrid cloud setup connecting an on-premise network to a cloud environment using GNS3 and Docker containers, secured with StrongSwan IPsec VPN. The topology integrates multiple network devices to simulate a real-world enterprise cloud deployment. The aim is to provide hands-on experience with routing, VPN configuration, and network testing between on-prem and cloud segments.

Devices Used
Cisco Router: R1-Cisco-Router (used for routing between on-prem and cloud networks)
Switches:
SW1-OnPrem-LAN (connects on-prem servers)
SW2-VPNTransit (connects VPN Gateway and router for secure tunnel)
SW3-Cloud-LAN (connects cloud server)
Servers / End Devices:
Ubuntu-OnPrem-Server (172.16.1.0/24 network)
Cloud-Server (10.0.0.0/24 network, Docker container)
StrongSwan-Gateway (IPsec VPN endpoint for secure tunnel)
NAT1 (for internet connectivity from StrongSwan-Gateway)
Network Overview
On-prem network: 172.16.1.0/24
Cloud network: 10.0.0.0/24
IPsec VPN tunnel between R1-Cisco-Router and StrongSwan-Gateway
All servers connected via respective switches and routed via R1 and VPN gateway

This topology allows simulation of secure communication, traffic routing, and connectivity testing across hybrid networks.
