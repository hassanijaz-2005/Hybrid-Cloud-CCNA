# Week 5 – VPN / IPsec Configuration
This week demonstrates the implementation of a secure VPN tunnel using IPsec between the on-premises Cisco router and the StrongSwan gateway in the cloud. 
**Devices:**
- Cisco Router (R1) – configured as VPN endpoint
- StrongSwan Gateway – cloud VPN endpoint
- On-Prem and Cloud Servers – test connectivity
- Switches – LAN connectivity
**Roles:**
- Muhammad Hassan Ijaz – Cisco Router Configuration & VPN Setup
- Muhammad Taufeeq Majeed – StrongSwan Configuration & Connectivity Testing
  **Key Commands Used:**
<img width="810" height="191" alt="Screenshot 2026-06-10 020105" src="https://github.com/user-attachments/assets/78cf1d0d-b2ce-45c5-8088-bf643b907dee" />
<img width="792" height="347" alt="CRYPTO MAP" src="https://github.com/user-attachments/assets/d724c72d-4ab5-4ae4-812b-02b22dd1e56e" />

- VPN tunnel established successfully
- Encrypted traffic verified via ping between on-prem and cloud networks
- All servers reachable via their respective LAN and VPN interfaces
