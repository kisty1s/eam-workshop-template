---
title: "Event 4: FCAJ Community Day - Agentic AI Showcase & Hackathon Demo Day"
date: 2026-07-26
weight: 4
chapter: false
pre: " <b> 4.4. </b> "
---

## Event Information

| Item | Details |
| --- | --- |
| Date | Sunday, July 26, 2026 |
| Location | AWS Vietnam Office, 26th Floor, Bitexco Financial Tower |
| Participation format | On-site participation & YouTube Livestream |
| Live Video | [Watch Live Video on YouTube](https://youtu.be/hz32VBrvW7M) |
| Role | Attendee |
| Main topics | Agentic AI Systems, Amazon Bedrock AgentCore, Multi-Channel Conversational Ordering, Computer Vision & Crowd Analytics, Automated Cloud Architecture, Corporate Signal Intelligence |
| Presenting Teams | **OneTeam** (KFC Bot Agent), **Team 3KA** (Project S.H.E.P.H.E.R.D), **Team Plan V** (SA Professional AI Native App), **Team Signal Scout** (Signal Scout Platform) |

## 2. Overview

The **FCAJ Community Day - Agentic AI Showcase & Hackathon Demo Day** (July 2026 edition) served as the grand showcase and deep-dive technical recap of breakthrough Agentic AI solutions built during the **Agentic AI Build Week (AABW)** hackathon. Bringing together top student engineers, builders, and AWS cloud experts, the event focused on advancing AI models from experimental prototypes into production-ready, commercialized enterprise systems.

Through architecture pitches and live demonstrations from 4 key teams (**OneTeam**, **3KA**, **Plan V**, and **Signal Scout**), attendees gained comprehensive insights into leveraging **Amazon Bedrock AgentCore**, **SageMaker**, **YOLO**, **Langfuse**, and AWS Cloud-Native services to solve real-world enterprise challenges across retail, operations management, cloud architecture, and strategic market intelligence.

## 3. Key Presenting Projects

### 3.1. OneTeam - AI-Powered Conversational Ordering Agent (KFC Bot Agent)

*   **Real-World Context & Problem:**
    *   Lessons from McDonald's AI drive-thru trial across 100+ US locations highlighted that conversational automated ordering is a **real system problem**. AI cannot merely answer questions; it must accurately understand item catalogs, quantities, variants, voucher rules, cart states, and error handling, as mistakes translate directly into monetary loss.
    *   Traditional human-only chat support fails to scale across shifts and traffic spikes. Forcing users to download or switch to separate mobile apps creates friction, causing lost customer momentum and abandoned orders.
*   **Solution (KFC Bot Agent):**
    *   A multi-channel conversational ordering agent operating directly within existing messaging channels (Zalo OA, WhatsApp, Messenger). Customers place orders without leaving the chat, downloading apps, creating accounts, or repeating instructions.
*   **Agentic Execution Flow (Goal -> Plan -> Tools -> Act -> Verify):**
    *   The model understands intent while tools govern factual actions across 5 steps: (1) Understand ordering intent -> (2) Plan required steps -> (3) Query trusted business data -> (4) Update cart & apply promotions -> (5) Verify against actual cart state.
    *   *"Design Once | Deploy Everywhere"* Architecture: Adding a channel requires only an Adapter, a new business system needs a Connector, and new capabilities require a Tool without rewriting core code.
*   **AWS Infrastructure & Cost Efficiency:**
    *   Leveraged **Amazon Bedrock AgentCore** to replace infrastructure layers, cutting **60% of infrastructure code**.
    *   End-to-end latency: **3 - 5 seconds** (from message sent to response received).
    *   Extremely cost-effective: **$0.006 per order** (at 500 orders/day); total infra cost ~$88/month (Bedrock accounting for 75%).
    *   **Achievement:** Won 1st Place at the AABW Hackathon!

### 3.2. Team 3KA - 24-Hour Hackathon Journey & Project S.H.E.P.H.E.R.D

*   **Problem & Inspiration:**
    *   Venue managers struggle to monitor entrances, queues, booths, and crowd movement across multiple areas simultaneously. Manual monitoring is slow, reactive, hard to scale, and prone to missed incidents during sudden congestion.
*   **S.H.E.P.H.E.R.D Solution (Smart Human-flow Evaluation, Prediction, Hazard Detection, Response, and Dispatch):**
    *   Converts ordinary camera feeds into actionable operational insights.
    *   Core capabilities: People detection and tracking, crowd density measurement, queue condition estimation, early congestion detection, overcrowding pressure prediction, proactive alerts, and staff dispatch recommendations.
*   **Technical Architecture & Agentic AI Layer:**
    *   *Computer Vision:* **YOLO + ByteTrack** for real-time object detection and tracking; **Amazon SageMaker** for cloud model inference.
    *   *Agentic AI Layer:* Combined **Amazon Bedrock AgentCore + Strands Agent** to build:
        *   *Autonomous Monitor:* Continuously analyzes crowd metrics, detects congestion risks, and fires proactive alerts.
        *   *Operator Copilot:* Conversational assistant enabling staff to query live operational metrics and receive recommended actions in natural language.
    *   *Dashboard:* React-based real-time monitoring interface.
*   **24-Hour Hackathon Reflections:**
    *   The team shared their journey overcoming initial obstacles with no prior AI background and limited AWS experience. Key takeaway: *"Showing up is half the battle"* and *"Small, finished work beats big, broken ideas."*

### 3.3. Team Plan V - Solution Architect Professional AI Native App

*   **Problem & Motivation:**
    *   Solution Architects spend hours reading BRD/PRD documents line-by-line, creating architecture diagrams from blank pages, manually writing IaC code, and estimating cloud costs based on subjective guesswork under tight deadlines.
*   **SA Professional AI Native App Solution:**
    *   An AI-native assistant for SAs: Analyzes natural language requirements and structured PRDs -> Drafts high-level, enterprise-aligned hybrid-cloud architecture options.
    *   Generates editable diagrams on **Draw.io** using official **AWS Architecture Icons**.
    *   Produces directional AWS service cost estimates tailored for the `ap-southeast-1` region.
    *   Identifies requirement gaps, assumptions, and recommendations, allowing iterative refinement via a Chat Sidebar.
*   **Impact:**
    *   Replaces manual document reading with structured Requirements Catalogs created in minutes.
    *   Replaces blank pages with grounded architectural drafts ready for review.
    *   Automates IaC generation and cost estimation alongside architecture diagrams.

### 3.4. Team Signal Scout - Early Corporate Strategic Signal Detection

*   **Problem & Challenges:**
    *   Enterprise strategy, risk management, and competitive intelligence teams struggle to connect scattered market signals, executive changes, and restructuring data into verifiable strategic insights.
*   **Signal Scout Solution:**
    *   An AI-powered platform for automated evidence collection and validation (via **Apify** and **TinyFish**), early detection of corporate restructuring signals, financial/operational metric analysis, and executive dashboard visualization.
    *   Supports leadership decisions to Maintain, Adapt, or Accelerate with transparent, evidence-backed reasoning.
*   **AWS Architecture & Cost Breakdown:**
    *   Comprehensive AWS Stack: **Amazon Bedrock**, **AgentCore Short-Term Memory & Runtime**, **AWS WAF**, **Amplify Hosting**, **CloudWatch**, **Secrets Manager**, **DynamoDB**, **Lambda**, **Route 53**, **CloudTrail**, **S3 Intelligent-Tiering**, **API Gateway HTTP**, **Cognito**, integrated with **Langfuse** for LLM observability.
    *   Detailed cost analysis across 3 scenarios: Min (approx. $81/mo), Mid (approx. $94/mo), and Max (approx. $359/mo), demonstrating cost-effective cloud architecture for enterprise AI agents.

## 4. Key Takeaways

*   **Maturation of Agentic AI on AWS:** Tools like **Amazon Bedrock AgentCore** simplify state management (Short-Term Memory), execution environments (Runtime), and tool integration, saving engineers up to 60% of infrastructure boilerplate code.
*   **System Mindset Over Simple Chatbots:** Production AI Agents must go beyond text generation to execute goal planning, query factual business data, perform action execution via Tool Calling, and verify results before completing transactions.
*   **FinOps & Cost Optimization:** Presentations from OneTeam ($88/mo) and Signal Scout ($81 - $94/mo) highlight that enterprise AI agent design must incorporate token cost optimization and serverless compute efficiency.
*   **Hackathon Mindset:** Rapid prototyping under time pressure requires strict scoping ("Scope it tiny"), clear role distribution, focusing on a core end-to-end MVP, and real-world validation.

## 5. Connection to the EAM Workspace Project

Key architecture lessons from the 4 presenting teams can be directly applied to enhance the EAM Workspace enterprise asset management system:
*   **Multi-Channel Asset Booking & Ticket Management (inspired by KFC Bot Agent):**
    *   Allow employees to request equipment, report asset issues, or schedule maintenance directly via Zalo/Slack without logging into the main web portal. The AI Agent verifies asset availability, updates reservation carts, and sends instant confirmations.
*   **Automated Infrastructure Mapping for EAM (inspired by SA Professional AI Native App):**
    *   Build automated IT Asset Infrastructure mapping tools to help IT managers visualize connections between servers, network devices, and associated cloud operational costs.
*   **Computer Vision Asset Monitoring & Warehouse Security (inspired by Project S.H.E.P.H.E.R.D):**
    *   Use AI Vision with IoT cameras to automatically track asset locations, detect equipment overheating or warehouse congestion, and trigger proactive maintenance alerts.
*   **Asset Lifecycle & Risk Intelligence (inspired by Signal Scout):**
    *   Combine asset usage signals, repair histories, and depreciation data into an Executive Dashboard to support leadership decisions on maintaining, servicing, or retiring assets.

## 6. Conclusion

The **FCAJ Community Day - Agentic AI Showcase & Hackathon Demo Day** demonstrated the paradigm shift toward Agentic AI. Leveraging the AWS ecosystem and sound cloud architecture enables teams to accelerate product development from months to 24 hours while unlocking tremendous opportunities for enterprise software systems like EAM Workspace.

## 7. Event Images

Some impressive photos recorded during the event at AWS Vietnam:

![AWS Agentic AI Build Week](/images/4-EventParticipated/4.4-Event4/fcaj-community-day-4.jpg)
