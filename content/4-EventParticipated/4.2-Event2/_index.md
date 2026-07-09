---
title: "Event 2: FCAJ Community Day"
date: 2026-06-27
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---


## Event Information

| Item | Details |
| --- | --- |
| Date | June 27, 2026 |
| Location | 26th and 36th Floors, Bitexco Financial Tower |
| Participation format | Online participation (Livestream via YouTube) |
| Role | Attendee |
| Main topics | Cloud Computing, AI Agent, Voice AI, DevOps AI Agent, AI in HR, and secure enterprise AI deployment |

## 2. Overview

FC Community Day is a monthly technology community event series that brings together experts and speakers from leading tech companies to share practical perspectives and project implementation experiences in enterprise environments. The June 2026 edition focused entirely on the shift from traditional cloud systems to the era of AI Agents to automate operations, optimize costs, enhance customer experience, and improve corporate governance.

The event holds high practical value for the tech community, thanks to the close connection between business problems, deep technical architecture, live demos on production infrastructure, and analyses of real-world architectural trade-offs.

## 3. Key Topics

### Cloud Agentic & Cloud Engineering Career Path

*   **Journey and Market Demand:** Speaker Steve Tran (Founder of Cloud Thinker, former Solution Architect at AWS) discussed the explosion of the cloud market during the pandemic when large corporations migrated their infrastructure to the cloud. This shift inevitably led to Microservices architectures, resulting in technical debt and increased operational complexities.
*   **Shifting Talent Standards:** Under the influence of AI, the IT recruitment market is freezing for general coding roles but highly demanding Senior talent capable of working optimally alongside AI. Future engineers cannot just write code; they must understand systems at the architectural level and use AI as a productivity lever.
*   **AI Agent Operations Solution:** Introduction of Cloud Thinker's Agentic Platform to assist humans in incident handling. The platform focuses on 4 core problems:
    *   *Incident Investigation* with log analysis speed measured in minutes instead of hours.
    *   *Infrastructure Code Review Automation* before deploying to Production.
    *   *Cost Optimization (FinOps)* automated via AI with a deep understanding of both financial aspects and AWS architecture.
    *   *Proactive Security Testing (Penetration Testing)* by packaging white-hat/black-hat hacker behaviors to continuously scan API vulnerabilities.
*   **Single Agent vs. Multi-Agent Architectural Trade-offs:** The discussion clarified that a well-designed Single Agent can complete over 95% of general tasks, but a Multi-Agent model (a system of specialized agents) wins in two key areas: cost optimization (using small, low-weight models for simple tasks and reserving large reasoning models for the coordinator Agent) and Role-Based Access Control (RBAC) within enterprise security boundaries.

### Voice AI for Vietnamese

*   **System Architecture:** Speakers Hieu Nghi (Renova Cloud), Kiet (AWS Student Builder), and Trung Do (CEO of R AI) analyzed two Voice AI architectural scenarios. While direct speech-to-speech models are currently optimized primarily for English, practical Voice Agent solutions in Vietnam must adopt a 3-stage bridge model: Speech-to-Text (STT) $\rightarrow$ Contextualization and processing via LLM $\rightarrow$ Text-to-Speech (TTS). The data flow is processed as continuous streaming from audio to text and fed directly into LLM/TTS to minimize response latency.
*   **Vietnamese Processing Challenges:** Vietnamese is classified as a low-resource language. The system must address specific challenges, including regional accents (accent recognition – datasets must contain 10-20% local dialects); real-time gender detection for correct honorifics ("Anh/Chi"); and training the model to handle natural interruptions, preventing the AI from cutting in when a customer pauses to think (e.g., when reciting a phone number).
*   **Application & Demo:** Kiet performed a Live Demo of a Voice Agent answering Apple product inquiries, deployed on Amazon Bedrock (Bedrock Agent Core) integrated with a Knowledge Base for Macbook models. Trung Do shared real-world experiences deploying Voice Agents for major banks in Vietnam (VPBank, VIB) to handle automated debt collection calls or emergency card-blocking workflows via tool calling.

### DevOps AI Agent

*   **Problem and Challenges:** Speakers Bao and Nguyen Nguyen (Cloud Engineers at Cloud Kinetics) highlighted the reality of mid-to-large-scale systems: when incidents occur, monitoring data is fragmented across multiple places (CloudWatch, CloudTrail, Grafana...) combined with knowledge silos between departments, leading to prolonged Mean Time to Detection (MTTD) and Mean Time to Resolution (MTTR).
*   **4-Step Operational Flow:**
    1.  *Triage:* Triggered automatically by system alerts or engineer queries, performing a quick aggregation of data.
    2.  *Investigation:* The AI Agent automatically builds a system Topology Graph containing hundreds of resource connections (ECS, Lambda, Database, IAM, Network...), generates failure hypotheses, and uses collected telemetry to prove/disprove them to find the root cause (Root Cause Analysis).
    3.  *Mitigation:* Generates step-by-step resolution scripts and command lines (Prepare $\rightarrow$ Validate $\rightarrow$ Execute $\rightarrow$ Post-validate), integrated with a chat interface with AI coding tools like Qodo or Cline for engineer review and approval (ensuring safety).
    4.  *Prevention:* Proposes long-term system upgrade plans based on the incident history.
*   **Live Demo and Case Study:** The demo session simulated a Mock DDoS attack sending 1,000 requests/second to an e-commerce application running on ECS behind an Application Load Balancer (ALB). The DevOps Agent automatically scanned the system, identified 10 overloaded ECS tasks, provided the exact terminal command to stop the faulty tasks, and restored the website to normal. The presentation shared real case studies like WGU (reducing MTTR by 77% from 2 hours to 28 minutes) and KDDI Japan (reducing incident resolution time from weeks to days).

### AI in Enterprise Human Resources

*   **HR Challenges:** Speakers Truong and Minh Anh (Noventic) pointed out bottlenecks in traditional HR processes, including manual CV screening that misses talent, subjective candidate evaluations, long Time to Hire impacting project timelines, and security risks of HR uploading candidate data to public AI platforms.
*   **Amazon Q (Amazon Quick) Solution:** AWS's Agentic AI tool allows setting up isolated data Spaces, connecting directly to internal storage (S3, OneDrive, Google Drive) or SaaS applications (Jira, GitHub, Salesforce). HR can train Amazon Q for specific roles (e.g., HR Talent Review Assistant) by feeding standard guidelines.
*   **Live Demo of Recruitment Flow:** Amazon Q automatically drafted a standard Job Description (JD); scanned and extracted text (OCR) from a folder of candidate resumes; scored and categorized candidates (Strong, Good, Low) based on a benchmark competency framework; and outputted a clean HTML report analyzing strengths/weaknesses and recommending a salary range within budget.

### Secure Enterprise AI Deployment (Private Security for Amazon Q)

*   **Security Vulnerabilities of Public AI:** Speakers Toan Nguyen (AWS Security Builder) and Hieu Nghi analyzed the risks when AI Agents connect to third-party systems/applications over the public Internet, including Denial of Service (DoS) attacks, expanded attack surfaces, and Man-in-the-Middle attacks causing sensitive data leaks.
*   **Private Security Network Architecture:** To ensure Zero Trust, the entire Model Context Protocol (MCP) Server – the protocol connecting AI to third-party applications (like Gmail, Zalo, Jira...) – must be placed entirely within a Private Subnet.
*   **Technical Workflow:** Amazon Q connects to internal systems via a VPC Connection (Interface Endpoint) and AWS secure networking solutions. The system uses a Route 53 Resolver to resolve private DNS (DNS existing only inside the VPC) and routes data traffic to an Application Load Balancer (ALB) integrated with TLS encryption certificates from AWS Certificate Manager (ACM). The entire query data flow is isolated within AWS's private network infrastructure and never travels over the public Internet, eliminating cybersecurity risks.

## 4. Key Takeaways

*   **Capability Shift:** The AI era will not replace engineers, but it will replace those who do not know how to leverage AI. Cloud and software engineers must shift their mindset to system architecture design and master AI tools to optimize operational productivity.
*   **"Human-in-the-loop" Principle:** For critical areas like Production infrastructure, the AI Agent only plays an advisory role (recommendation only). The final decision-making power always remains with humans to ensure system safety and cultural alignment.
*   **Data Quality Decides AI Performance:** The reasoning power of a DevOps AI Agent depends entirely on the maturity of the monitoring system (Good Observability). Without sufficient log, metric, and alarm data, the AI cannot formulate accurate conclusions.
*   **Information Security is Pre-requisite:** When integrating AI into enterprise operations, isolated network architectures and internal data permission controls (Private VPC, AWS PrivateLink, MCP Server) are mandatory to meet strict security standards.

## 5. Connection to the EAM Workspace Project

The insights from FCAJ Community Day offer valuable lessons that can be directly applied to optimize the EAM Workspace enterprise asset management system:
*   **Standardizing DevOps & Operations:** To ensure stable system operations as asset and staff scales grow, the project should focus on establishing clear logging, strict user authorization, optimized health checks, and monitoring alerts (Alarm) to proactively manage system failures and minimize MTTR.
*   **Future AI Integration Roadmap:** EAM Workspace can expand with smart Agentic features based on the secure integration patterns learned:
    *   Integrate an internal virtual assistant (like Amazon Q using private data spaces) to help employees quickly query asset status and locations using natural language.
    *   Automate technical support by using AI to read and categorize incoming asset repair tickets.
    *   Build an AI Agent to analyze operational history to suggest smart periodic asset maintenance schedules or quickly compile asset reports.

## 6. Conclusion

FCAJ Community Day provided a practical view of the modern technology shift. Building enterprise software is not just about implementing features; it must simultaneously address operations, security, scalability, and user experience in a real Production environment.

## Event Images

Some images recorded during the event:

![FC Community Day](/images/4-EventParticipated/4.2-Event2/fcaj-community-day-1.png)

![FC Community Day](/images/4-EventParticipated/4.2-Event2/fcaj-community-day-2.png)

![FC Community Day](/images/4-EventParticipated/4.2-Event2/fcaj-community-day-3.png)
