---
title: "Week 5 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---

The fifth week of the internship shifted focus toward high-availability infrastructure architectures, load distribution, and system performance optimization on AWS. The core content included conducting comprehensive research and hands-on configurations of Elastic Load Balancing (ELB) and Auto Scaling Groups (ASG). Additionally, system deployment testing and performance stress evaluations were executed to analyze structural resilience under high-traffic simulations.

### Week 5 Objectives:
* Deeply research the operation and architecture of AWS high-availability components.
* Practice configuring Elastic Load Balancing (ELB) to distribute inbound application traffic across multiple instances.
* Set up Auto Scaling Groups (ASG) to dynamically adjust compute capacity based on system load.
* Execute practical deployment testing and evaluate overall system scaling performance.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| Fri | - Research the concepts of high availability, fault tolerance, and load balancing on AWS.<br>- Learn about the types of Elastic Load Balancers (ALB, NLB, GLB).<br>+ Document baseline criteria for selecting appropriate load balancers. | 18/05/2026 | 18/05/2026 | Project source code, Team discussion, <https://cloudjourney.awsstudygroup.com/> |
| Sat | - Learn how to configure an Application Load Balancer (ALB) via the AWS Console.<br>- Study target groups, health check configurations, and routing rules.<br>+ Map out target instances for the load distribution setup. | 19/05/2026 | 19/05/2026 | AWS Management Console, Team discussion, <https://cloudjourney.awsstudygroup.com/> |
| Sun | - Research the operational mechanism of AWS Auto Scaling and Launch Templates.<br>- Learn about horizontal vs. vertical scaling and dynamic scaling policies.<br>+ Define threshold rules (CPU, memory) for scale-out and scale-in actions. | 20/05/2026 | 20/05/2026 | Project source code, Team discussion, <https://cloudjourney.awsstudygroup.com/> |
| Mon | - Practice configuring Launch Templates with designated Amazon Machine Images (AMI).<br>- Set up an Auto Scaling Group (ASG) integrated with the previously created ALB.<br>+ Verify initial minimum, desired, and maximum instance constraints. | 21/05/2026 | 21/05/2026 | AWS Management Console, Team discussion, <https://cloudjourney.awsstudygroup.com/> |
| Tue | - Execute test deployments of the web application within the auto-scaling infrastructure.<br>- Monitor instance registration status and health metrics through the ALB dashboard.<br>+ Log baseline resource behaviors during standard operations. | 22/05/2026 | 22/05/2026 | AWS Management Console, Team discussion, <https://cloudjourney.awsstudygroup.com/> |
| Wed | - Conduct system performance stress testing using benchmarking tools to simulate traffic surges.<br>- Analyze how the Auto Scaling Group reacts to high load and triggers new instances.<br>+ Evaluate scaling latency and data integrity during resource expansion. | 23/05/2026 | 23/05/2026 | AWS Management Console, Terminal, <https://cloudjourney.awsstudygroup.com/> |
| Thu | - Consolidate test metrics, performance charts, and load balancing verification logs.<br>- Document optimization steps taken and resolve configuration anomalies in scaling policies.<br>+ Finalize the weekly progress report and prepare integration goals for the next phase. | 24/05/2026 | 24/05/2026 | AWS Management Console, Team discussion, <https://cloudjourney.awsstudygroup.com/> |

### Week 5 Achievements:
* Gained a solid understanding of high-availability cloud designs, fault-tolerant methods, and traffic distribution rules.
* Successfully configured an Application Load Balancer (ALB) with automated target groups and strict health checks.
* Proficiently established Auto Scaling Groups (ASG) utilizing dynamic launch templates to automate instance scaling.
* Successfully completed load simulation tests, validating the environment's ability to self-heal and auto-scale under high loads.

### Plan for the Next Week:
* Shift focus to containerization technologies by deep-diving into Docker fundamentals.
* Practice writing Dockerfiles, building container images, and deploying containerized applications on AWS.
* Learn about configuring the AWS CLI (Command Line Interface) to manage cloud infrastructure from local environments.
