# Lab 05 - Router Communication Between Different Networks

## Objective

The objective of this lab was to understand how a router enables communication between two different networks.

---

## Topology

PC1 → Switch1 → Router → Switch2 → PC2

---

## Devices Used

- 2 PCs
- 2 Switches
- 1 Router

---

## Cable Used

Copper Straight-Through Cable

---

## IP Configuration

### PC1

- IP Address: 192.168.1.10
- Subnet Mask: 255.255.255.0
- Default Gateway: 192.168.1.1

### PC2

- IP Address: 192.168.2.10
- Subnet Mask: 255.255.255.0
- Default Gateway: 192.168.2.1

### Router

#### Interface G0/0

- IP Address: 192.168.1.1

#### Interface G0/1

- IP Address: 192.168.2.1

---

## Commands Used

Enable interfaces:

```
no shutdown
```

Testing connectivity:

```
ping 192.168.2.10
```

---

## Result

The ping was successful because the router forwarded packets between two different networks.

---

## What I Learned

- Routers connect different networks.
- Routers use IP addresses to forward packets.
- A Default Gateway is required for communication between different networks.
- Without a router, devices on different networks cannot communicate.

---

## Skills Practiced

- Router configuration
- IP Address configuration
- Default Gateway configuration
- Basic troubleshooting
- Packet testing using ping

---

## SOC Analyst Connection

This lab helped me understand how traffic moves between networks. This knowledge is important for investigating network communication issues, firewall rules, routing problems, and security incidents as a future SOC Analyst.
