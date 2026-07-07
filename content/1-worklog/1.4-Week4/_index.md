---
title: "Week 4 Worklog"
date: 2026-05-12
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---
### Week 4 Objectives:
* Deep dive into identity and access management operations using AWS IAM.
* Understand structure logic of security permissions using IAM Policies and permissions boundaries.
* Learn and configure multi-factor authentication mechanisms via MFA setup.
* **Hands-on:** Build a robust, enterprise-grade Secure multi-user environment.
### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Research foundational theoretical frameworks governing AWS IAM.<br> - Differentiate core components: IAM Users, IAM Groups, and IAM Roles. | 05/11/2026   | 05/11/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Analyze JSON-based IAM Policy structures (Effect, Action, Resource, Condition elements).<br> - Apply the Principle of Least Privilege to authorization models. | 05/12/2026   | 05/12/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Study security risks concerning root account management and administrative infrastructure access.<br> - Learn standard operational flows for MFA setup. | 05/13/2026   | 05/13/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Prepare an isolation blueprint case-study: drafting custom access parameters across separated EC2 nodes and specific storage S3 buckets. | 05/14/2026   | 05/14/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Hands-on Practice:** Build and initialize a functional Secure multi-user environment.<br> - Establish Dev/Test groups, enforce scoped permission policies, and mandate active MFA. | 05/15/2026   | 05/15/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Week 4 Achievements:

* Mastered Core Identity & Security Concepts:
  * Clearly distinguished when to provision IAM Users (for human operators) versus IAM Roles (for temporary cross-service authorization).
  * Gained the ability to parse and build customized JSON IAM Policies from scratch to achieve granularity, moving beyond default AWS managed permissions.
* Enhanced Cloud Infrastructure Hardening Mindset:
  * Understood the security imperatives behind locking down the Root Account and isolating daily operational tasks.
  * Successfully set up and enforced virtual Multi-Factor Authentication (MFA) parameters on administrative accounts to block credential leakage vectors.
* Hands-on Engineering Accomplishments:
  * Simulating enterprise delegation by successfully partitioning environments into dedicated Dev groups (restricted to EC2 actions) and Test groups (restricted to S3 reads).
  * Validated policy enforcement: verified that out-of-scope API commands or unauthorized actions across distinct asset segments were systematically dropped by the IAM evaluation engine.
