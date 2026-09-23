Enterprise Network Infrastructure & Security

A Cisco Packet Tracer project demonstrating the design and configuration of an enterprise-style network with routing, switching, network segmentation, firewall protection, and a DMZ.

Network Architecture

The network consists of:

Router1 — Connects the internal network to the firewall
Router2 & Router3 — Provide routing within the internal network
SW1 & SW2 — Cisco 2960 Layer 2 switches for internal network connectivity
ASA Firewall — Controls traffic between the internal network, DMZ, and ISP
Switch4 — Dedicated DMZ switch
Server-5, Server-6, Server-7 — Servers located in the DMZ
Server-1, Server-2, Server-3, Server-4 — Internal network servers
ISP — Represents the external network/Internet
Technologies & Concepts
IPv4 addressing
VLANs
Static routing
Dynamic routing
OSPF
EtherChannel
SSH
DHCP
Cisco ASA firewall
DMZ architecture
Network segmentation
Access control
Network troubleshooting
Security Architecture

The ASA firewall separates the internal network from external and DMZ networks.

The DMZ contains servers that are separated from the internal network to reduce the security impact of exposing services to external networks.

Internal servers remain within the protected internal network.

Routing

Routers are used to provide connectivity between different network segments.

OSPF is used to demonstrate dynamic routing and exchange routing information between participating routers.

Switching

SW1 and SW2 are Cisco 2960 Layer 2 switches used to connect internal devices and servers.

EtherChannel can be used to combine multiple physical links into a single logical connection, providing increased bandwidth and redundancy.

Remote Management

SSH is configured for secure remote management of network devices.
