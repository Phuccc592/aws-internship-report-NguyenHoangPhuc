---
title: "Week 3 Worklog"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives:
* Study and master the core concepts of cloud virtual network architecture (Amazon VPC).
* Deeply understand multi-tier network security, routing configuration, and traffic control.
* **Hands-on Practice:** Successfully build a secure Multi-tier network architecture*as a foundation for deploying Web and Database systems.
### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Research theoretical concepts of Amazon VPC.<br> - Learn how to plan IP ranges and divide network subnets: Public Subnet, Private Subnet, Internet Gateway (IGW), and Route Tables. | 05/04/2026   | 05/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Analyze and compare network-level firewalls.<br> - Design a network access control matrix. | 05/05/2026   | 05/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Study identity management with AWS IAM: Manage Users, Groups, and Advanced Policies based on the Principle of Least Privilege.<br> - Configure specific IAM Roles for secure cross-service connections. | 05/06/2026   | 05/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Study Network Address Translation to grant one-way outbound Internet access for resources in secure Private Subnets.<br> - Optimize internal network traffic routing. | 05/07/2026   | 05/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Hands-on Practice:** Deploy a practical **Multi-tier network architecture** within the Amazon VPC environment.<br> - Configure secure routing between the Web Server and Database Server. | 05/08/2026   | 05/08/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Week 3 Achievements:

* Mastered Cloud Networking Architecture:
  * Understood CIDR block allocation and how to divide Public/Private Subnets according to information security standards.
  * Mastered packet routing mechanisms using Route Tables and the critical role of Internet Gateways for public-facing resources.

* Developed Multi-Tier Network Defense Skills:
  * Distinguished and applied both Security Groups (for instance-level traffic control) and Network ACLs (for subnet-level gateway filtering).
  * Successfully deployed a NAT Gateway, ensuring the Database Backend can fetch necessary system updates and patches while remaining completely hidden from external Internet threats.

* Acquired Identity & Access Management (IAM) Skills:
  * Proficiently wrote and customized JSON-based IAM Policies. Created and attached IAM Roles to compute resources to eliminate hardcoded Access Keys.

* Hands-on Implementation Results:
  * Independently built a functional VPC network with optimized segmentation. Successfully verified tier-to-tier connectivity: clients can access the public Web tier, but only the Web tier is permitted to route internal database queries down to the private Database tier.
