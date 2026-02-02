# Network Exposure & Hardening Lab

## Objective
Set up a virtualized lab environment to analyze the network exposure of a Linux machine,
intentionally expose a service (SSH), and then secure it using a firewall.

## Environment
- VMware Workstation
- Ubuntu Desktop
- Kali Linux
- NAT network

## Lab Steps
1. Setup of Ubuntu and Kali virtual machines
2. Network connectivity verification (ping)
3. Initial scan from Kali (no open ports detected)
4. Installation and activation of the SSH service on Ubuntu
5. Network scan showing port 22 open
6. Firewall (UFW) activation with SSH allowed
7. Final validation scan from Kali

## Results
- Before SSH: no exposed ports
- After enabling SSH: port 22 open
- After firewall activation: only port 22 accessible

## Conclusion
This lab demonstrates that exposing a service increases the attack surface.
A firewall allows precise control over exposed services.
External validation from another machine is essential.
