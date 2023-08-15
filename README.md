# AWS VPC and Network Infrastructure

This repository contains a set of AWS CloudFormation templates in YAML format that help you set up a Virtual Private Cloud (VPC) along with various network infrastructure components. These components include a VPC, Internet Gateway, Subnet, Route Table, and Network ACL. The templates are written in CloudFormation YAML syntax and are designed to be easily customizable based on your requirements.

## Template Contents

1. `vpc.yaml`: This template creates a Virtual Private Cloud (VPC) with the specified CIDR block.

2. `internet_gateway.yaml`: Creates an Internet Gateway and attaches it to the previously created VPC.

3. `subnet.yaml`: Defines a public subnet within the VPC.

4. `route_table.yaml`: Creates a Route Table with an internet route and associates it with the public subnet.

5. `network_acl.yaml`: Defines a Network ACL with inbound and outbound rules to allow HTTP and HTTPS traffic.

## Getting Started

1. Clone this repository to your local environment:

   ```sh
   git clone https://github.com/AngelofVerdant/chatGPT-yaml-file.git
