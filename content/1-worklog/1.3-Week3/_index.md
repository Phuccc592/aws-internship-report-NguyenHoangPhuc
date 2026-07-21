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
| 4   | - Explored AWS IAM identity frameworks (Users, Groups, Policies) enforcing the Principle of Least Privilege.<br>- Configured IAM Roles for cross-resource service permissions. | 05/06/2026   | 05/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Configured NAT Gateways to grant outbound internet connectivity for Private Subnet workloads while blocking inbound traffic. | 05/07/2026   | 05/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | Architected and deployed a production-grade multi-tier VPC network.<br>- Configured isolated routing between Web Application tier and Database tier. | 05/08/2026   | 05/08/2026      | <https://cloudjourney.awsstudygroup.com/> |


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
