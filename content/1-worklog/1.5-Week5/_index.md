---
title: "Week 5 Worklog"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
### Week 5 Objectives:
* Explore the Serverless Computing paradigm, focusing on deploying independent code execution units via Lambda and configuring their associated triggers.
* Learn how to structure and set up API Gateway endpoints to receive and map incoming HTTP/HTTPS requests.
* Study NoSQL data modeling patterns and core storage management operations within Amazon DynamoDB.
* **Hands-on:** Build and deploy a secure, serverless REST API backend to handle full CRUD workflows.
### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Study serverless architectural definitions and Event-driven system design.<br> - Investigate AWS Lambda execution lifecycles, memory boundaries, and automatic event trigger integrations. | 05/18/2026   | 05/18/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Research Amazon API Gateway infrastructure: designing stable REST resources, resource paths (GET, POST, PUT, DELETE), and setting up Proxy integrations with Lambda. | 05/19/2026   | 05/19/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Explore Amazon DynamoDB schemas: defining proper Partition Keys (PK) and Sort Keys (SK).<br> - Analyze structural performance between Query, Scan, PutItem, and UpdateItem operations. | 05/20/2026   | 05/20/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Draft backend data flow diagrams defining application logic parameters for handling structured CRUD pipelines.<br> - Prepare codebases using JavaScript/Node.js to power Lambda processes. | 05/21/2026   | 05/21/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Hands-on Practice:** Coordinate and build a full serverless REST API backend using API Gateway, AWS Lambda handlers, and DynamoDB storage.<br> - Verify operational endpoints using Postman. | 05/22/2026   | 05/23/2026      | <https://cloudjourney.awsstudygroup.com/> |

### Week 5 Achievements:
* Mastered Serverless Development Principles:
  * Acquired clear insights into the benefits of serverless environments: automated elastic scaling, pay-per-use costing models (paying only for precise execution blocks), and absolute abstraction of host maintenance.
  * Successfully bound environment variables and strict IAM execution role policies to give Lambda processing units minimal, granular read/write authorizations over target DynamoDB resources.
* Constructed and Integrated Industry-Standard APIs:
  * Understood foundational configurations for API Gateway deployment, successfully mitigating CORS (Cross-Origin Resource Sharing) blockages and managing payload validation boundaries.
  * Realized specific execution trade-offs regarding storage reads, systematically prioritizing efficient Query calls over costly, resource-heavy tables-wide Scan actions within DynamoDB environments.
* Hands-on Engineering Accomplishments:
  * Independently delivered a highly resilient, fully operational serverless REST API backend system.
  * Demonstrated flawless end-to-end processing loops: external client triggers hit designated API Gateway routes requests immediately spin up targeted AWS Lambda computing scripts  logic runs and securely mutates states directly inside scalable Amazon DynamoDB tables.
