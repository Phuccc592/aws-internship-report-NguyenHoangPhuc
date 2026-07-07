---
title: "Week 8 Worklog"
date: 2026-06-08 
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---
### Week 8 Objectives:
* Study resource observation methodologies, telemetry metric collection, and automated threshold alerts via CloudWatch metrics and alarms.
* Understand infrastructure operation visibility, user API activity tracking, and security posture auditing with CloudTrail audit logging.
* Explore request cycle behaviors across distributed microservices topologies utilizing X-Ray distributed tracing.
* **Hands-on:** Design, execute, and stabilize a centralized, multi-service.
### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Study core definitions of cloud infrastructure observability Metrics, Logs, and Alarms primitives.<br> - Investigate CloudWatch configurations for collecting EC2 and Lambda telemetry. | 06/08/2026   | 06/08/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Construct operational CloudWatch Alarms hooked to automated SNS notification pipelines triggered during spikes.<br> - Setup CloudWatch Logs stream agents. | 06/09/2026   | 06/09/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Research AWS CloudTrail operations: intercepting multi-region API control-plane activities and routing tamper-proof audit trails into dedicated secure S3 buckets. | 06/10/2026   | 06/10/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Explore AWS X-Ray distributed tracing blueprints: integrating application SDK interceptors to map multi-tier system request telemetry and identify latency bottlenecks. | 06/11/2026   | 06/11/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Hands-on Practice:** Coordinate and deploy a unified Comprehensive monitoring setup binding CloudWatch, CloudTrail, and X-Ray components.<br> - Simulate high load states, verify warning signals. | 06/12/2026   | 06/12/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Week 8 Achievements:
* Mastered Cloud System Observability & Telemetry Principles:
  * Developed a proactive system management mindset, prioritizing early trend diagnostics over reactive hot-fixing after unexpected service degradations occur.
  * Cultivated practical debugging capabilities, isolating operational application errors through consolidated stream logs and immutable audit data evaluation.
* Proficiently Handled Standard Cloud Observability Tooling:
  * Constructed functional real-time anomaly alarm architectures by routing strategic CloudWatch warning thresholds directly to active administrator messaging targets.
  * Tracked asynchronous requests across microservice topologies using interactive AWS X-Ray service maps, effortlessly pinpointing optimization areas inside underlying compute units or storage layers.
* Hands-on Engineering Accomplishments:
  * Independently delivered a secure, stable, and unified Comprehensive monitoring setup. The deployment ensures robust system visibility: control plane actions are securely logged by CloudTrail, compute resource variations are metricated by CloudWatch, and microservice communication pathways are visually traced by AWS X-Ray.