# Subnetting

## What is Subnetting?

Subnetting is the process of dividing a larger network into smaller networks called subnets.

## Why Do We Use Subnetting?

- Better network organization
- Efficient use of IP addresses
- Smaller broadcast domains
- Improved network management
- Can improve security and isolation

## How Subnetting Works

Subnetting works by borrowing bits from the host portion of an IP address and using them as network bits.

## Important Formulas

Number of subnets:

2^n

Where n = number of borrowed bits.

Usable hosts per subnet:

2^h - 2

Where h = number of remaining host bits.

## Example

Network: 192.168.1.0/24

If we borrow 2 host bits:

/24 → /26

Borrowed bits = 2

Number of subnets:

2^2 = 4

Remaining host bits = 6

Usable hosts per subnet:

2^6 - 2 = 62

Therefore, a /24 network can be divided into 4 /26 subnets, with 62 usable host addresses in each subnet.

## What I Learned

- Subnetting divides a network into smaller networks.
- CIDR notation tells us how many bits are used for the network portion.
- Borrowing host bits creates additional subnets.
- More network bits means more subnets but fewer hosts per subnet.
