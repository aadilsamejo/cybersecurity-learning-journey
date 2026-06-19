# Networking Task 04 - Different Networks Communication

## Objective

Understand why devices on different networks cannot communicate directly through a switch.

## Topology

PC1 ----- Switch ----- PC2

## IP Configuration

### PC1

IP Address: 192.168.1.10

Subnet Mask: 255.255.255.0

### PC2

IP Address: 192.168.2.10

Subnet Mask: 255.255.255.0

## Testing

Attempted to ping PC2 from PC1.

Command Used:

ping 192.168.2.10

## Results

Ping failed.

No successful replies were received.

## Observations

- The devices belonged to different networks.
- The switch forwarded traffic.
- The destination device rejected the communication.
- No router was available to route traffic between the two networks.

## Important Learning

Devices on different networks require a router or Layer 3 device to communicate.

A switch alone cannot route packets between different networks.

## Skills Learned

- IP Addressing
- Network Identification
- Routing Fundamentals
- Troubleshooting Connectivity Issues

## Author

Aadil Ahmed

SOC Analyst Learning Journey
