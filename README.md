# CCNA Labs Portfolio

A collection of hands-on Cisco CCNA labs completed in Cisco Packet Tracer while preparing for the CCNA (200-301) exam. Every lab was configured and tested by hand, from basic switching to routing, IP services, security and wireless.

**Author:** Randy M. Flores · [LinkedIn](https://linkedin.com/in/randy-flores232323) · [CCNA badge (Credly)](https://www.credly.com/badges/dcb83fc4-44f6-4182-9f04-060c760f5cae/public_url)

## ⭐ Featured: CCNA Mega Lab

**`CCNA MEGA LAB.pka`** is the centerpiece of this repository: one large Packet Tracer lab that covers every topic of the CCNA in a single network. Switching and VLANs, routing, IP services, security and wireless all work together in one topology, much like a real network.

The lab was created by **Jeremy's IT Lab (JITL)** as part of his free CCNA course ([jeremysitlab.com](https://www.jeremysitlab.com)). I completed it myself in Packet Tracer as part of my CCNA preparation. Credit for the lab design and topology goes to JITL.

If you open only one file here, open this one.

## What This Repository Covers

The labs are split into two sets:

1. **Day-by-day study labs**: a structured set that follows the CCNA topics in order, from connecting devices to wireless LANs.
2. **Additional hands-on labs**: 29 further Packet Tracer labs, focused on routing, redundancy, IP services, security and troubleshooting.

Topics covered across both sets:

- VLANs, trunking, DTP, VTP, EtherChannel and multilayer switching
- Spanning Tree Protocol (STP, Rapid STP) and its link with HSRP
- Static and floating static routes, VLSM
- OSPF, OSPFv3 and EIGRP, including route summarization
- First-hop redundancy with HSRP
- IPv4 and IPv6 addressing, IPv6 static routes
- Access control lists (standard, extended, named)
- NAT and PAT (static, dynamic, overload)
- DHCP, DHCP relay, DHCP snooping, DNS, NTP, SNMP, Syslog, SSH, FTP and TFTP
- Port security, Dynamic ARP Inspection, GRE tunnels
- Wireless LANs and wireless LAN controllers (WLC), voice VLANs and QoS

## Set 1: Day-by-Day Study Labs

### Core Networking
- Day 02 Lab - Connecting Devices
- Day 03 Lab - OSI Model
- Day 04 Lab - Basic Device Security
- Day 06 Lab - Ethernet LAN Switching
- Day 09 Lab - Interfaces
- Day 11 Lab - Configuring Static Routes
- Day 11 Lab - Troubleshooting Static Routes
- Day 12 Lab - Life of a Packet
- Day 15 Lab - VLSM

### Switching and VLANs
- Day 16 Lab - VLANs (Part 1)
- Day 17 Lab - VLANs (Part 2)
- Day 18 Lab - Multilayer Switching
- Day 19 Lab - DTP & VTP
- Day 20 Lab - Analyzing STP
- Day 21 Lab - Configuring Spanning Tree
- Day 22 Lab - Rapid STP
- Day 23 Lab - EtherChannel
- Day 52 Lab - STP & HSRP Synchronization

### Routing and Redundancy
- Day 24 Lab - Floating Static Routes
- Day 25 Lab - EIGRP Configuration
- Day 29 Lab - HSRP Configuration
- Day 31 Lab - IPv6 Configuration (Part 1)
- Day 32 Lab - IPv6 Configuration (Part 2)
- Day 33 Lab - IPv6 Static Routes
- Day 53 Lab - GRE Tunnels

### Security and Access Control
- Day 34 Lab - Standard ACLs
- Day 35 Lab - Extended ACLs
- Day 44 Lab - Static NAT
- Day 45 Lab - Dynamic NAT
- Day 49 Lab - Port Security
- Day 50 Lab - DHCP Snooping
- Day 51 Lab - Dynamic ARP Inspection

### Services, Management and Wireless
- Day 37 Lab - NTP
- Day 38 Lab - DNS
- Day 39 Lab - DHCP
- Day 40 Lab - SNMP
- Day 41 Lab - Syslog
- Day 42 Lab - SSH
- Day 43 Lab - FTP & TFTP
- Day 46 Lab - Voice VLANs
- Day 47 Lab - QoS
- Day 58 Lab - Wireless LANs

## Set 2: Additional Hands-On Labs (29 labs)

These labs go deeper into routing, redundancy, services and troubleshooting. Several combine more than one technology in a single topology.

### Switching
- STP Lab
- STP Lab 2
- Trunking Lab
- VLAN Lab
- Switching Mastery: VLANs and Access Ports (2 lab files)

### Routing
- Static Routes
- Routing Lab 1
- OSPF Fundamentals
- OSPF Config Lab
- OSPFv3 Lab
- OSPF + SSH Labs
- OSPF + EIGRP Summarization
- IPv6 Lab
- IPv6 Lab 2

### Redundancy
- HSRP
- HSRP Lab 2

### IP Services and Security
- DHCP
- DHCP Lab
- DHCP Snooping
- DHCP Relay, SNMP, OSPF, Logging and NTP Lab
- DNS Lab
- NAT / PAT
- ACL Standard Basic Lab
- ACL Extended Lab
- ACL Named Extended Lab

### Wireless
- WLC
- WLC Troubleshooting (not tagging other VLANs)

### Combined
- Week Mega Lab

## Other Files

- `CCNA MEGA LAB.pka`: the featured all-topics lab (see above)
- `Day 16 activity.txt`: activity notes for the VLAN labs
- `Day 32 cisco Labs.txt`: extra notes and lab references for IPv6
- `day 13 quiz.txt`: quiz and study notes

## How to Use

1. Install [Cisco Packet Tracer](https://www.netacad.com/) and open a lab file (`.pkt`, or `.pka` for the archive).
2. Read the topology and lab objectives before changing anything.
3. Configure the devices, then check connectivity with `ping`, `traceroute` and the relevant `show` commands.
4. Compare your result with the lab goal, and use the notes files where one is provided.

## Related Projects

Beyond Packet Tracer, I also built two larger labs on virtual routers:

- [Redundant-Network-Failover-Lab](https://github.com/Kioski22/Redundant-Network-Failover-Lab): four VyOS routers in GNS3 running OSPF with BFD, with measured failover tests and troubleshooting tickets.
- [NOC-Monitoring-Lab](https://github.com/Kioski22/NOC-Monitoring-Lab): a monitoring environment in GNS3 and VMware using LibreNMS, SNMPv3, syslog, Discord alerts and Oxidized config backups.

## License

Shared for educational and portfolio purposes.
