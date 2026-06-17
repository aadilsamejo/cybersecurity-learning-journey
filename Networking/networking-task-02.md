# Networking Task 02 - Three PC Network

## Objective

Create a LAN consisting of three PCs connected through a switch and test communication between all devices.

## Topology

PC1
 \
  \
   Switch
  /     \
PC2     PC3

## IP Configuration

### PC1
192.168.1.10

### PC2
192.168.1.20

### PC3
192.168.1.30

Subnet Mask:
255.255.255.0

## Testing Performed

- PC1 → PC2
- PC1 → PC3
- PC2 → PC3

## Results

All devices successfully communicated with each other.

No packet loss was observed.

## Observations

- The switch initially broadcast ARP requests.
- Devices learned MAC addresses.
- Communication became direct after address resolution.


## Skills Learned

- LAN Communication
- Switch Operation
- ARP Basics
- MAC Address Learning
- Connectivity Testing

## Author

Aadil Ahmed
SOC Analyst Learning Journey
