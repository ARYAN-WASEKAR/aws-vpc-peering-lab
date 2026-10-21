# AWS VPC Peering Lab

## Project Overview
This project demonstrates how to establish private communication between two Amazon Virtual Private Clouds (VPCs) using AWS VPC Peering.

## Objectives
- Create two separate VPCs with non-overlapping CIDR blocks.
- Configure public and private subnets.
- Establish a VPC peering connection.
- Configure route tables and security groups.
- Verify private communication between EC2 instances.

## AWS Resources
- Amazon VPC
- Public and private subnets
- VPC Peering Connection
- EC2 instances
- Route tables
- Internet Gateway
- Security groups

## Network Configuration

| Resource | Private IP / CIDR |
|---|---|
| VPC A | 10.10.0.0/16 |
| VPC B | 10.20.0.0/16 |
| App-A | 10.10.2.10 |
| App-B | 10.20.1.10 |
| Bastion Host | 10.10.1.10 |

## Testing and Results
Successfully tested ICMP communication from App-A to App-B using their private IP addresses. The test returned 4 packets received with 0% packet loss.

## Learning Outcomes
Learned how VPC peering, routing, security groups, private subnets, and bastion-host access work together in AWS.

## Author
Aryan Wasekar

## Important Security Note
Private keys, passwords, AWS access keys, account credentials, and other secrets are not included in this repository.
