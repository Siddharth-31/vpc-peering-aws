# 🌐 AWS VPC Peering Project

This project demonstrates secure private communication between two Amazon Virtual Private Clouds (VPCs) using **AWS VPC Peering**. It focuses on cloud networking, routing, security configuration, and cost management through hands-on AWS implementation.

## 📌 Project Overview

- ✅ Created two VPCs: `Prod-VPC` and `Test-VPC` with non-overlapping CIDR blocks.
- ✅ Launched EC2 instances in public and private subnets.
- ✅ Established a VPC Peering connection for private communication between VPCs.
- ✅ Configured route tables to enable traffic flow between the VPCs.
- ✅ Configured security groups to control inbound and outbound traffic.
- ✅ Set up a NAT Gateway to provide internet access to private subnet resources.
- ✅ Configured Internet Gateways for public subnet connectivity.
- ✅ Monitored AWS usage and expenses using Billing and Cost Explorer.
- ✅ Documented the architecture, configuration, and troubleshooting steps.

## 🧱 Architecture Diagram

**AWS VPC Peering Architecture**

The architecture consists of two isolated VPCs connected through a VPC Peering connection. Route tables and security groups control communication between resources, while the NAT Gateway enables outbound internet access for private subnet resources.

> Add your architecture diagram here to illustrate the VPCs, subnets, EC2 instances, route tables, and network gateways.

## 🚀 AWS Services Used

| AWS Service | Purpose |
|---|---|
| Amazon VPC | Create isolated virtual networks |
| Amazon EC2 | Host instances for connectivity testing |
| VPC Peering | Enable private communication between VPCs |
| NAT Gateway | Provide outbound internet access to private subnets |
| Elastic IP | Provide a static public IPv4 address for the NAT Gateway |
| Internet Gateway | Enable internet connectivity for public subnet resources |
| Route Tables | Define network traffic routes |
| Security Groups | Control instance-level network traffic |
| AWS Billing & Cost Explorer | Monitor and analyze AWS costs |

## 📸 Project Screenshots

The `/screenshots` folder contains screenshots documenting the project configuration and implementation, including:

- EC2 Instances
- VPCs and Subnets
- Route Tables and Routes
- VPC Peering Connection
- NAT Gateway and Elastic IP
- Internet Gateway
- Security Groups
- AWS Billing and Cost Explorer

## 🧪 Testing and Validation

- Verified connectivity between EC2 instances across the peered VPCs.
- Checked route table entries for correct traffic forwarding.
- Reviewed security group rules for the required communication.
- Tested internet connectivity from private subnet instances through the NAT Gateway, where configured.
- Reviewed AWS billing to identify potentially expensive resources.

*Include only the tests you actually completed and verified.*

## 💡 Key Learnings

- Understood how VPC Peering enables private communication between VPCs.
- Learned the differences between public and private subnets.
- Gained practical experience configuring route tables and security groups.
- Learned how Internet Gateways and NAT Gateways differ.
- Practiced troubleshooting network connectivity issues.
- Understood AWS networking costs and potential charges for NAT Gateways and public IPv4 addresses.
- Learned the importance of monitoring billing and deleting unused resources.

## 💰 Cost Management

AWS resources such as NAT Gateways and public IPv4 addresses can incur charges, depending on the resource configuration and applicable pricing.

To manage costs:

- Monitor usage through AWS Billing and Cost Explorer.
- Delete unused NAT Gateways, Elastic IPs, and EC2 instances.
- Remove unnecessary resources after completing testing.
- Review current AWS pricing before deploying resources.

## 🛠️ Technologies Used

**Amazon Web Services (AWS) | VPC | EC2 | VPC Peering | Networking | Linux | Cloud Infrastructure**

## 👨‍💻 Author

**Siddhant Pawar**

BE Information Technology | Aspiring DevOps Engineer

GitHub: [Siddharth-31](https://github.com/Siddharth-31)
