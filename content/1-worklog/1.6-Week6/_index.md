---
title: "Week 6 Worklog"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
### Week 6 Objectives:
* Study application integration patterns and message distribution services, focusing on Amazon SQS queues and Amazon SNS pub/sub models.
* Learn serverless event routing mechanisms and event bus configurations with Amazon EventBridge.
* Explore advanced workflow orchestration and design state management models using AWS Step Functions.
* **Hands-on:** Build and validate a decoupled, robust Event-driven architecture.
### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Research microservices integration concepts and enterprise asynchronous messaging structures.<br> - Study message queues using Amazon SQS and pub/sub patterns via Amazon SNS. | 05/25/2026   | 05/25/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Investigate Amazon EventBridge structures: setting up custom event buses and writing routing Rules to track system resource mutations. | 05/26/2026   | 05/26/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Explore AWS Step Functions orchestration blueprints: designing structural Workflows via visual State Machines and handling logic branches. | 05/27/2026   | 05/27/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Design loose-coupling patterns: creating fan-out pipelines binding SNS Topics to automated SQS Queues while enforcing secure cross-service access parameters. | 05/28/2026   | 05/28/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Hands-on Practice:** Coordinate and deploy a full serverless Event-driven architecture pattern.<br> - Simulate event triggers, monitor branching logic inside Step Functions, and verify real-time SNS email notifications. | 05/29/2026   | 05/31/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Week 6 Achievements:
* Mastered Event-Driven Structural Concepts:
  * Acquired solid insights into Loose Coupling application models, ensuring components function independently to bolster system fault tolerance and reduce processing bottlenecks.
  * Successfully architected a Fan-out messaging pattern by binding Amazon SNS alerts straight into concurrent Amazon SQS queues for parallel data consumption.
* Orchestrated Sophisticated Enterprise Workflows:
  * Proficiently applied Amazon EventBridge filters to listen to specific infrastructure alerts and accurately dispatch payload signals to background operational workers.
  * Utilized Amazon States Language (ASL) syntax within AWS Step Functions to build deterministic retry boundaries, coordinate logic branches, and maintain execution state transparency.
* Hands-on Engineering Accomplishments:
  * Independently built and stabilized a decoupled Event-driven infrastructure system.
  * Demonstrated flawless message routing telemetry: upstream lifecycle state triggers  EventBridge intercepts and forwards payloads Step Functions orchestrates conditional state execution pipelines Amazon SNS pushes immediate system alerts to administrator endpoints.