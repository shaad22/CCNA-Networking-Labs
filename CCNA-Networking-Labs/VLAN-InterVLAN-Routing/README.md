# VLAN and Inter-VLAN Routing Lab

## Objective

To configure multiple VLANs and enable communication between different VLANs using Router-on-a-Stick.

## Network Topology

The lab consists of a Cisco router, Cisco switch, and multiple end devices connected across different VLANs.

## Devices Used

- Cisco Router
- Cisco Switch
- PCs
- Cisco Packet Tracer

## Technologies Used

- VLAN
- Inter-VLAN Routing
- Router-on-a-Stick
- IEEE 802.1Q
- IPv4 Addressing
- Cisco IOS

## VLAN Configuration

| VLAN | Name | Network |
|------|------|---------|
| 10 | HR | 40.0.0.0/8 |
| 20 | SALES | 30.0.0.0/8 |
| 30 | IT | 50.0.0.0/8 |

## Configuration

The switch was configured with multiple VLANs, and the router was configured with subinterfaces for Inter-VLAN Routing.

Each VLAN was assigned a separate IP subnet and default gateway.

## Verification

The following tests were performed:

- Verified VLAN configuration
- Verified trunk connectivity
- Verified router subinterfaces
- Tested default gateway connectivity
- Tested communication between different VLANs using ping

## Files

- `VLAN-InterVLAN-Routing.pkt` - Cisco Packet Tracer project
- `topology.png` - Network topology screenshot
- `router-config.txt` - Router configuration
- `switch-config.txt` - Switch configuration