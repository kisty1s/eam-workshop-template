---
title: "Event 1: AWS First Cloud Journey Community Day"
date: 2026-06-06
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---


| Information | Details |
| --- | --- |
| Date | June 6, 2026 |
| Location | 26th Floor, Bitexco Financial Tower |
| Participation format | On-site participation |
| Role | Attendee |
| Main topics | Cloud Computing, DevOps, Security, AI, WebSocket, Teamwork, and career orientation in information technology |
| Speakers | Tran Trung Vinh - System Administrator at Central Retail Group;<br>Bao Huynh - Junior Cloud Native Developer, Endava Vietnam;<br>Le Hoang Gia Dai, Nguyen Quoc Bao, Truong Huy Phuoc, Viet Phat |

## 1. Purpose of participating in the event

The AWS First Cloud Journey Community Day served as a high-value professional seminar designed to help students and cloud engineering beginners bridge the gap between academic theory and practical industry insights. By gathering experts currently operating in the enterprise tech sector, the event provided participants with a comprehensive understanding of how modern technologies—such as AWS, Docker, Machine Learning, WebSocket, GraphRAG, and DevOps workflows—are integrated and deployed in real-world production environments.

My primary objectives for attending the event included:
*   **Expanding Knowledge Beyond the Classroom:** Moving past fundamental theoretical concepts to deeply understand advanced application deployment, system security compliance, and real-time cloud architectures.
*   **Observing Industry Best Practices:** Learning directly from how seasoned IT professionals break down complex technical problems, propose enterprise-grade solutions, and share production-level post-mortems.
*   **Career Roadmap Development:** Gaining critical insights into career progression within the Cloud and DevOps domains to align my current competencies with corporate expectations.

## 2. Main content of the event

The community day comprised a series of diverse, specialized sharing sessions. While each presentation targeted a unique sub-discipline of technology, they collectively unified around a singular goal: building comprehensive, multi-layered technical capabilities for modern AWS practitioners.

### 2.1. Docker - A Containerization Technology

This session introduced the core concepts of containerization technology and emphasized the irreplaceable role of Docker within contemporary software development, testing, and deployment life cycles. The speaker provided a comparative analysis between traditional Virtualization and Containerization, highlighting why containers are significantly lighter, more resource-efficient, and inherently more scalable for modern cloud-native infrastructures.

*   **Key Insight:** Docker is far more than a tool for running isolated applications; it is the backbone of continuous integration and continuous delivery (CI/CD) pipelines in modern DevOps workflows. By packaging source code, system libraries, configurations, and runtime dependencies into unified containers, engineering teams can eliminate the notorious "it works on my machine" discrepancy between local environments, staging servers, and production.
*   **AWS Alignment:** Mastery of Docker serves as a prerequisite foundation for working with advanced orchestration services on AWS, such as Amazon ECS (Elastic Container Service) and Amazon EKS (Elastic Kubernetes Service).

### 2.2. Machine Learning-based Network Intrusion Detection System (NIDS) on AWS

Centered around modern cyber security paradigms, this session deep-dived into securing web applications against evolving threat landscapes using AWS WAF (Web Application Firewall) coupled with artificial intelligence. The speaker demonstrated how AWS WAF acts as an edge defense layer to mitigate standard OWASP Top 10 vulnerabilities, including SQL Injection, Cross-Site Scripting (XSS), automated botnets, and brute-force attacks.

*   **Key Insight:** Traditional static rule-based firewalls, while effective against predefined, historical threat signatures, inherently struggle to mitigate novel zero-day attacks or polymorphic anomalous activities. To overcome these limitations, the session proposed integrating AWS WAF with Machine Learning models to construct a robust Network Intrusion Detection System (NIDS) capable of continuously learning from active network telemetry to identify behavioral anomalies.
*   **Security Shift:** Cloud security is transitioning rapidly from traditional signature-based static defenses toward dynamic, predictive behavior-based automated response models.

### 2.3. From IT Helpdesk to Senior Sysadmin

This career orientation session provided highly relatable, actionable guidance based on the speaker’s personal journey from entry-level technical support (IT Helpdesk) to managing complex enterprise infrastructures as a Senior System Administrator.

*   **Key Insight:** Progressing into high-level infrastructure roles demands an unyielding stability-oriented mindset, advanced troubleshooting methodologies, systematic documentation habits, comprehensive monitoring workflows, and extreme caution (e.g., enforcing strict safety policies and never testing directly in production without a verified rollback plan).
*   **The Paradigm Shift:** The speaker highlighted the critical mindset shift required when moving from legacy, rigid On-Premise environments to the Cloud, focusing on elastic scalability, pay-as-you-go cost optimization, leveraging fully managed services, and utilizing Infrastructure as Code (IaC). Growth in cloud computing dictates that an engineer must reinforce their core fundamentals in operating systems (particularly Linux), networking protocols, and automation script writing before managing high-level abstractions.

### 2.4. Multiplayer in the Cloud - Connecting Godot Clients with AWS WebSockets

This deeply technical session explored the architectural design of real-time bidirectional communication by connecting Godot engine game clients via AWS WebSocket protocols. The speaker performed a technical trade-off analysis between standard data communication protocols—such as UDP/ENet, WebSocket, and HTTP Polling—outlining the distinct advantages, limitations, and optimal use cases for each.

```
[Godot Game Clients] <---> [Amazon API Gateway (WebSocket)] <---> [AWS Lambda] <---> [Amazon DynamoDB]
                                                                        |
                                                                [Amazon CloudWatch]
```

*   **Key Insight:** The demonstrated production architecture leveraged Amazon API Gateway to maintain persistent stateful connections with clients, AWS Lambda to process event-driven backend business logic asynchronously, Amazon DynamoDB to store real-time connection states with minimal latency, and Amazon CloudWatch for central logging and analytics.
*   **Architecture Value:** This architecture provided a concrete example of a highly scalable Serverless design pattern, enabling real-time applications (such as game lobbies, chat systems, or streaming dashboards) to scale dynamically without the overhead of maintaining or provisioning traditional virtual servers.

### 2.5. The Art of Effective Teamwork

Recognizing that software engineering is inherently collaborative, this session shifted focus toward the human side of technology, outlining four fundamental pillars required to maximize engineering team velocity and project success:
*   **Aligned Goals:** Ensuring every team member has crystal-clear, shared objectives.
*   **Optimal Resource Placement:** Assigning the right technical tasks to individuals based on their core strengths.
*   **Open Communication & Active Listening:** Establishing psychological safety for constructive, transparent feedback loops.
*   **Personal Accountability:** Maintaining an ownership mindset regarding individual deliverables.
*   **Recommended Tooling Ecosystem:** The session introduced modern agile project management and communication suites—including ClickUp, Trello, Slack, Google Workspace, and Discord—to systematically track progress, organize sprints, and centralize technical documentation. This is highly practical for academic group projects and corporate internships alike.

### 2.6. GraphRAG - Build GraphRAG Applications Using Amazon Bedrock and Amazon Neptune

The final session introduced cutting-edge trends within Generative AI, specifically exploring GraphRAG—an advanced paradigm that combines traditional Retrieval-Augmented Generation (RAG) with structural Knowledge Graphs.

*   **Key Insight:** Traditional RAG searches for context using vector similarity across document chunks, which often falls short when user queries require deep, multi-hop reasoning across highly interconnected data points. GraphRAG solves this by structuring information as an interconnected web of nodes (entities) and edges (relationships).
*   **Implementation Stack:** The speaker showcased how to build these complex architectures using Amazon Bedrock to orchestrate foundational Large Language Models (LLMs) alongside Amazon Neptune as the managed graph database engine. This highlighted that modern cloud platforms have evolved far beyond basic computation and storage providers, now operating as comprehensive ecosystems for deploying intelligent, semantic data-driven AI systems.

## 3. Lessons learned

Attending this event provided a profound blend of technical, career, and interpersonal insights:
*   **Technical Upskilling:** I consolidated my understanding of Docker's role in environment parity, AWS’s capability in scaling event-driven serverless architectures, and the imperative shift toward multi-layer behavioral security. Advanced topics like GraphRAG and WebSocket connections illustrated the immense breadth of the AWS ecosystem across varied domains.
*   **Career Roadmap:** The transformation story from Helpdesk to Sysadmin reinforced that sustainable career growth in Cloud and DevOps demands a rock-solid grasp of baseline fundamentals—specifically Linux administration, advanced networking, telemetry monitoring, script automation, and deep documentation skills.
*   **Soft Skills Integration:** I learned that technical brilliant is incomplete without streamlined collaboration. Implementing shared goals, maintaining absolute accountability, and utilizing modern agile project management tools are mandatory for delivering successful corporate-level tech projects.

## 4. Personal contribution

During the community day, I executed several intentional activities to maximize the value of my attendance:
*   **Active Documentation:** I systematically took structured notes on architecture diagrams, service integrations, and best practices across AWS, containerization, and AI modules to serve as high-quality reference material for my academic and internship reports.
*   **Knowledge Synthesis:** I actively mapped the real-world methodologies shared by the enterprise speakers against the baseline theoretical concepts I had previously studied within the AWS Study Group program, identifying specific gaps in my knowledge.
*   **Actionable Learning Plan Adjustment:** Post-event, I translated my notes into a structured self-study plan. Moving forward, I will prioritize hands-on practice in packaging multi-tier applications using Docker, deploying serverless microservices on AWS, and experimenting with basic IAM and WAF security configurations within my personal lab environment.

## 5. Conclusion

In summary, the AWS First Cloud Journey Community Day was an exceptionally impactful experience that broadened my perspective on the velocity of the modern cloud computing landscape. The sessions successfully demystified how individual AWS components interconnect to solve complex corporate challenges, while clearly defining the precise skill matrices expected by the tech industry in 2026.

The event has left me deeply motivated to continue my technical trajectory, equipping me with the technical clarity and strategic focus necessary to pursue upcoming roles in Cloud Engineering, DevOps, and Backend Architecture.

## Event Images

Some images recorded during the event:

![AWS First Cloud Journey Community Day](/images/4-EventParticipated/4.1-Event1/z7976498940486_4005b6c6d8361abe3f1b76bdf4dd74ef.jpg)
