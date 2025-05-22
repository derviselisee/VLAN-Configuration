# VLAN-Configuration

This hands-on project simulated a small enterprise network using Cisco Packet Tracer, involving:

1 Router, 2 Layer 2 Switches, and 10 PCs

4 logically separated departments configured with VLANs:

VLAN 10 – IT (192.168.10.0/24)

VLAN 20 – HR (192.198.20.0/24)

VLAN 30 – Sales (192.168.30.0/24)

VLAN 40 – Accounting (192.168.40.0/24)

Each VLAN was configured on different switch ports, and inter-VLAN communication was enabled through router-on-a-stick using subinterfaces on the router. Trunk links between switches and the router were configured for VLAN tagging using 802.1Q encapsulation.


Skills Gained
- Network Design & Topology Building
Designed and mapped an enterprise-style LAN using Cisco devices

Assigned VLANs based on department needs for logical segmentation.

IP Addressing & Subnetting
Assigned static IPs to PCs within correct VLAN subnets

Ensured no IP conflicts and matched each PC to its gateway

-Troubleshooting & Validation
Verified connectivity using:

ping between devices in the same and different VLANs

show vlan brief, show interfaces trunk, and show ip route

Diagnosed and fixed VLAN mismatches and trunk misconfigurations

- Security & Broadcast Control
Isolated network traffic between departments to reduce broadcast domains

Secured switch port access to prevent unauthorized VLAN access
