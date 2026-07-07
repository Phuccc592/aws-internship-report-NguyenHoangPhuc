---
title: "Week 1 Worklog"
date: 2026-04-17
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Week 1 Objectives:

* Connect and get acquainted with members of First Cloud Journey.
* Understand basic AWS services, how to use the console & CLI.
* Successfully deploy a simple web server on the Cloud platform.

### Tasks carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| **6** | - Get acquainted with FCJ members <br> - Read and take note of internship unit rules and regulations | 04/17/2026 | 04/17/2026 | FCJ Portal |
| **2** | - Learn about AWS and core service groups: <br>&emsp; + Compute (EC2, Lambda) <br>&emsp; + Storage (S3, EBS) <br>&emsp; + Networking (VPC, Route53) <br>&emsp; + Database (RDS, DynamoDB) | 04/20/2026 | 04/20/2026 | [AWS Workshop](https://cloudjourney.awsstudygroup.com/) |
| **3** | - Create AWS Free Tier account <br> - Learn about AWS Console & AWS CLI <br> - **Practice:** Install & configure AWS CLI | 04/21/2026 | 04/21/2026 | [AWS Documentation](https://docs.aws.amazon.com/) |
| **4** | - Learn basic EC2: <br>&emsp; + Instance types, AMI, EBS <br>&emsp; + Security Groups & Key Pairs <br> - SSH connection methods to EC2 | 04/22/2026 | 04/23/2026 | [AWS Workshop](https://cloudjourney.awsstudygroup.com/) |
| **6** | - **Practice:** <br>&emsp; + Launch an EC2 instance & connect via SSH <br>&emsp; + Attach an EBS volume <br>&emsp; + Install & configure Apache Web Server | 04/24/2026 | 04/24/2026 | [AWS Workshop](https://cloudjourney.awsstudygroup.com/) |

### Week 1 Achievements:

#### 1. Knowledge and Tools
* Mastered the basic AWS service groups: Compute, Storage, Networking, and Database.
* Successfully created and configured an AWS Free Tier account.
* Installed and configured AWS CLI (Access Key, Secret Key) on the local machine.

#### 2. AWS EC2 Practice
* Launched the WebServer instance running Amazon Linux 2023 successfully.
* Configured Security Groups to allow traffic on port 80 (HTTP) and port 22 (SSH).
* Used key Pair (Phuc-Key) for secure system authentication.

#### 3. Web Server Deployment
* Installed and activated Apache Web Server (httpd) on the EC2 instance.
* Personalized the website to display: "Nguyen Hoang Phuc - AWS Web Server Live!" at Public IP: `100.53.10.33`.

![Web Server Success](/images/WebServer.png)
