---
title: "Week 2 Worklog"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

### Week 2 Objectives:

* Connect and get acquainted with members of First Cloud Journey.
* Understand basic AWS services, how to use the console & CLI.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Research Amazon S3 buckets <br> - Learn how to configure and set up storage lifecycle policies on S3 | 04/27/2026 | 04/27/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Study Amazon EBS block storage service <br> - Analyze EBS volume management and data backup mechanisms using Snapshots | 04/28/2026 | 04/28/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Learn about the Amazon RDS relational database service <br> - Study the process of initialization, configuration setup, and database administration (RDS setup and management) | 04/29/2026 | 04/29/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - **Practice (Hands-on):** Initialize secure S3 storage components and configure access permissions <br> - Design and develop a file upload system to the cloud (Build file upload system) | 04/30/2026 | 05/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Practice (Hands-on):** Initialize and link an Amazon RDS database instance <br> - Finalize application source code, establishing synchronous connection between the file storage layer and the database layer | 05/01/2026 | 05/02/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Week 2 Achievements:

* Mastered the foundational knowledge and architectural workflow of core service groups:
  * **Amazon S3:** Object storage concepts, managing access permissions, and optimizing long-term storage costs using automated S3 Lifecycle rules.
  * **Amazon EBS:** Block storage attached to Amazon EC2 virtual servers, modifying volume capacity dynamically, and creating secure data backups using Snapshots.
  * **Amazon RDS:** Managing cloud-based relational database instances that automate routine tasks such as patching, backups, and horizontal scaling.

* Successfully performed hands-on configuration of secure Amazon S3 buckets and implemented lifecycle transition rules (such as moving objects from S3 Standard to Glacier or setting up automatic expiration policies for temporary files).

* Gained practical experience in cloud block storage administration, including creating new EBS volumes, attaching them to a running Linux server, and executing system commands to mount the partitions.

* Successfully deployed an Amazon RDS instance (MySQL/SQL Server) and mastered Security Group configurations to authorize secure incoming traffic from internal VPC subnets.

* **Completed the Hands-on Project:** Developed and deployed a functioning file upload application that stores media assets securely in an Amazon S3 bucket while tracking and indexing file metadata inside an Amazon RDS instance.
* ...