# BGP / EIGRP / GRE over IPsec Lab

This project demonstrates a hands-on networking lab focused on dynamic routing, secure tunneling, and traffic protection across ISP connections.

## Project Overview
In this lab, I built and tested a routed environment using:
- **BGP** for ISP/WAN route exchange
- **EIGRP** for internal routing
- **GRE Tunnel** for logical connectivity between routers
- **IPsec** to encrypt LAN traffic across the WAN

## What I implemented
- Configured BGP neighbor relationships between routers
- Controlled preferred path selection to the ISP
- Built a GRE tunnel between edge routers
- Applied IPsec protection to secure tunnel traffic
- Verified that internal LAN traffic was encrypted
- Tested routing, reachability, and traffic flow across the lab

## Key skills demonstrated
- BGP configuration and path selection
- EIGRP internal routing
- GRE tunnel deployment
- IPsec VPN configuration
- Routing verification and troubleshooting
- Network security fundamentals

## Verification
- Confirmed tunnel status and reachability
- Verified encrypted traffic using IPsec-related show commands
- Tested LAN-to-LAN communication across the secure tunnel

## Tools / Platform
- EVE-NG
- Cisco routers
- Virtual PCs for end-to-end testing

## Objective
The goal of this lab was to understand how enterprise routers can securely carry internal traffic over ISP networks while maintaining routing control and encryption.
