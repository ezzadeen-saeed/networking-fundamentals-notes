# IP Addressing and Subnetting — Exercise 01

## Objective
Understand IPv4 addresses and identify devices in the same IPv4 subnet using a /24 prefix.

## Example
- Device A: 192.168.1.10/24
- Device B: 192.168.1.25/24
- Device C: 192.168.2.25/24

## Explanation
A /24 prefix corresponds to subnet mask 255.255.255.0. In this example, the network address is 192.168.1.0 and the broadcast address is 192.168.1.255.

Device A and Device B belong to the same subnet: 192.168.1.0/24.
Device C belongs to a different subnet: 192.168.2.0/24.

## Key Takeaway
With a /24 prefix, the first three octets identify the subnet. Devices in different subnets may communicate through a router, depending on the network configuration.

## Learning Status
This is an introductory worked example. More subnetting exercises will be added as I progress.
