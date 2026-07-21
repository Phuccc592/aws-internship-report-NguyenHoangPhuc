---
title: "Week 2 Worklog"
date: 2026-04-27
weight: 2
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
| 3   | - Investigated Amazon EBS block storage, volume management strategies, and Snapshot backup mechanisms. | 04/28/2026 | 04/28/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | -- Studied Amazon RDS relational database engine, automated snapshot workflows, and management practices. | 04/29/2026 | 04/29/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Initialized S3 bucket storage structures and configured granular access policies. | 04/30/2026 | 05/01/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Designed and deployed an end-to-end cloud file upload system powered by Amazon S3. | 05/01/2026 | 05/02/2026 | <https://cloudjourney.awsstudygroup.com/> |


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