# NAT Overload + DHCP Relay + NTP Verification

## Objective
Enable DHCP relay for remote LANs, configure NAT Overload for Internet access, and synchronize router clocks using NTP. Verify client IP assignment and time synchronization.

### Skills Learned
- Configuring DHCP relay to forward requests to a central DHCP server.
- Setting up NAT Overload (PAT) for multiple internal clients.
- Synchronizing router clocks using NTP.
- Verifying NAT translations and DHCP bindings.

### Tools Used
- Routers R1 and R2.
- Packet Tracer.
- Commands: `show ip dhcp binding`, `show ip nat translations`, `show ntp status`.

## Steps
1. Configure DHCP relay on R2 to forward requests to R1.
2. Set up NAT Overload on R2’s Internet interface.
3. Configure NTP client on both routers using 209.165.200.10.
4. Test clients for automatic IP assignment.
5. Verify NAT translations using `show ip nat translations`.
6. Check NTP synchronization with `show ntp status`.

*Ref 1: Network Diagram*  
![Network Diagram](imgsrc)
