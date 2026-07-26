---
title: "Event 4: FCAJ Community Day - Agentic AI Showcase & Hackathon Demo Day"
date: 2026-07-20
weight: 4
chapter: false
pre: " <b> 4.4. </b> "
---

## Event Information

| Item | Details |
| --- | --- |
| Date | Saturday, July 25, 2026 |
| Location | AWS Vietnam Office, 26th Floor, Bitexco Financial Tower |
| Participation format | On-site participation |
| Role | Attendee |
| Main topics | Agentic AI Systems, Amazon Bedrock AgentCore, Multi-Channel Conversational Ordering, Computer Vision & Crowd Analytics, Automated Cloud Architecture, Corporate Signal Intelligence |
| Presenting Teams | **OneTeam** (KFC Bot Agent), **Team 3KA** (Project S.H.E.P.H.E.R.D), **Team Plan V** (SA Professional AI Native App), **Team Signal Scout** (Signal Scout Platform) |

## 2. Overview

The **FCAJ Community Day - Agentic AI Showcase & Hackathon Demo Day** (July 2026 edition) was an exceptionally inspiring and practical sharing session. At this event, I had the valuable opportunity to sit directly in the audience at the AWS Vietnam office, listening to senior student engineers and builders who had just completed the **Agentic AI Build Week (AABW) Hackathon** take the stage to present their architectures, share battle-tested experiences, and demonstrate their Agentic AI solutions live.

Throughout the morning, the team members stepped up onto the stage to pitch their cloud system architectures (Architecture Pitch), recount their intense 24-hour build journeys, and perform live on-site demonstrations right before our eyes. Watching them showcase how to leverage **Amazon Bedrock AgentCore**, **SageMaker**, **YOLO**, **Langfuse**, and AWS Cloud-Native services provided me with real-world lessons that go far beyond standard classroom theory.

## 3. Key Presenting Projects

### 3.1. OneTeam - AI-Powered Conversational Ordering Agent (KFC Bot Agent)

*   **Real-World Context & Problem:**
    *   On stage, Team OneTeam began by analyzing a real-world case study from McDonald's AI drive-thru trial in the US, emphasizing that conversational automated ordering is a **real system problem**. AI cannot merely answer simple questions; it must accurately process item catalogs, quantities, variants, promo rules, cart states, and error handling, as mistakes directly impact revenue.
    *   They also highlighted that traditional human-only chat support cannot scale during traffic spikes, while requiring customers to download a new app creates friction and lost momentum.
*   **Solution (KFC Bot Agent):**
    *   The team introduced a Multi-channel Conversational Ordering Agent operating seamlessly within everyday chat apps like Zalo OA, WhatsApp, and Messenger. Customers can place orders directly within the chat without downloading new apps or registering new accounts.
*   **Agentic Execution Flow (Goal -> Plan -> Tools -> Act -> Verify):**
    *   They explained the 5-step operational flow: (1) Understand ordering intent -> (2) Plan required steps -> (3) Query trusted business data -> (4) Update cart & apply promotions -> (5) Verify against actual cart state.
    *   *"Design Once | Deploy Everywhere"* Architecture: Adding a new messaging channel requires only an Adapter, connecting a new business system needs a Connector, and adding capabilities only requires a new Tool.
*   **AWS Infrastructure & Cost Efficiency:**
    *   Leveraging **Amazon Bedrock AgentCore**, they saved up to **60% of infrastructure code**.
    *   Sitting in the audience watching their live demo as they placed a test order via Zalo OA, I was amazed by the ultra-fast response time of just **3 - 5 seconds**.
    *   Their calculated cost model was also remarkably optimized: ~$0.006 per order, with a total monthly infrastructure cost of ~$88 (Bedrock accounting for 75%).
    *   **Achievement:** Their outstanding presentation earned them 1st Place in the AABW Hackathon amidst enthusiastic applause from the entire room!

### 3.2. Team 3KA - 24-Hour Hackathon Journey & Project S.H.E.P.H.E.R.D

*   **Problem & Inspiration:**
    *   When Team 3KA took the stage, the atmosphere became warm and inspiring. They shared the challenge of venue security monitoring: venue managers struggle to simultaneously track entrances, queues, booths, and crowd flows. Manual monitoring is reactive, labor-intensive, and prone to missing incidents during sudden crowd surges.
*   **S.H.E.P.H.E.R.D Solution:**
    *   The project converts standard camera video streams into real-time operational metrics: detecting and tracking people, measuring crowd density, estimating queue conditions, detecting congestion risks early, and dispatching alerts to staff.
*   **Technical Architecture & Agentic AI Layer:**
    *   *Computer Vision:* **YOLO + ByteTrack** for object detection and tracking; **Amazon SageMaker** for cloud inference.
    *   *Agentic AI Layer:* Combined **Amazon Bedrock AgentCore + Strands Agent** to create an Autonomous Monitor (automated crowd analysis & alert dispatch) and an Operator Copilot (conversational assistant querying live operational data via natural language).
    *   *Dashboard:* A React monitoring interface showcased live on the big screen.
*   **24-Hour Hackathon Reflections:**
    *   Listening to the team share their journey of pulling an all-nighter for 24 hours, starting without a deep AI background and working with AWS for the first time, was genuinely inspiring. Their key message to the audience was deeply memorable: *"Showing up is half the battle"* and *"Small, finished work beats big, broken ideas."*

### 3.3. Team Plan V - Solution Architect Professional AI Native App

*   **Problem & Motivation:**
    *   Team Plan V's presentation resonated strongly with the engineers in the room by addressing a major pain point: Solution Architects spend hours reading BRD/PRD documents line-by-line, creating architecture diagrams from blank pages, writing IaC code manually, and estimating cloud costs based on subjective guesswork under tight deadlines.
*   **SA Professional AI Native App Solution:**
    *   The team presented an AI-native assistant for SAs: Automatically reads and analyzes requirement documents -> Drafts enterprise-grade hybrid-cloud architecture options.
    *   Generates editable architecture diagrams on **Draw.io** using official AWS Architecture Icons.
    *   Outputs real-time AWS cost estimates tailored for the `ap-southeast-1` region.
    *   Identifies requirement gaps and enables SAs to refine architectures iteratively via a Chat Sidebar.
*   **Impact:**
    *   Watching them perform the live demo on stage, the app transformed a raw requirements document into a complete architecture diagram, IaC code, and cost estimation in just minutes, drawing nods of approval from everyone in the room.

### 3.4. Team Signal Scout - Early Corporate Strategic Signal Detection

*   **Problem & Challenges:**
    *   Team Signal Scout presented a polished topic on corporate strategic intelligence: Risk management and corporate strategy teams face difficulties connecting fragmented information (executive changes, restructuring news, market shifts) into a clear, evidence-backed picture.
*   **Signal Scout Solution:**
    *   An AI platform that automatically collects and validates evidence (combining **Apify** and **TinyFish**), detects restructuring signals early, and visualizes data on an Executive Dashboard to support Maintain, Adapt, or Accelerate decisions.
*   **AWS Architecture & Cost Breakdown:**
    *   They presented a comprehensive AWS architecture: **Amazon Bedrock**, **AgentCore**, **AWS WAF**, **Amplify**, **CloudWatch**, **DynamoDB**, **Lambda**, **Route 53**, integrated with **Langfuse** for LLM observability.
    *   Their detailed cost analysis across 3 usage scenarios (ranging from Min ~$81/mo to Max ~$359/mo) was praised by AWS experts in the audience for its financial pragmatism.

## 4. Key Takeaways

Spending the morning listening to the presenting teams share their real-world build experiences provided me with valuable takeaways:
*   **AWS Support for Agentic AI:** Listening to their explanations helped me better understand how **Amazon Bedrock AgentCore** simplifies memory management (Short-Term Memory), runtime environments, and tool integrations, saving up to 60% of infrastructure effort.
*   **System Problem Solving Mindset:** A successful production AI agent goes beyond generating nice chat replies; it must follow a structured flow of planning, querying trusted data, executing tool calls, and verifying accuracy before concluding actions.
*   **FinOps & Practical Cost Management:** Learning from their cost calculations ($88/mo or $81-$94/mo), I realized that designing enterprise AI systems requires optimizing token usage and selecting suitable Serverless services.
*   **Hackathon Product Mindset:** Hearing their reflections on their 24-hour hackathon journey taught me the importance of scoping down ("Scope it tiny"), dividing roles effectively, and focusing on finishing a single core working feature rather than trying to build everything.

## 5. Connection to the EAM Workspace Project

The architectures and lessons shared on stage by the teams inspired several practical ideas for the EAM Workspace project (Enterprise Asset Management System):
*   **Inspired by OneTeam (KFC Bot Agent):** Build a multi-channel AI assistant for asset requests/repairs on Zalo/Slack. Employees can message to report broken equipment or request assets; the AI Agent verifies inventory, updates status, and sends instant confirmations.
*   **Inspired by Plan V (SA AI App):** Build a feature that automatically drafts IT asset infrastructure maps and calculates associated cloud operational costs for each asset in EAM.
*   **Inspired by Team 3KA (S.H.E.P.H.E.R.D):** Apply AI Vision with warehouse cameras to track equipment locations, detect overheating, and automatically dispatch maintenance alerts.
*   **Inspired by Signal Scout:** Create an Executive Dashboard analyzing maintenance history, usage frequency, and depreciation data to help management decide whether to Replace, Maintain, or Retire assets.

## 6. Conclusion

Attending the **FCAJ Community Day - Agentic AI Showcase & Hackathon Demo Day** at the AWS Vietnam office was an amazing learning experience. Sitting in the audience, listening to senior builders share their hard-earned lessons, watching live product demos, and seeing architecture breakdowns gave me tremendous perspective. The knowledge and inspiration gained from this event will be invaluable assets as I apply them to my studies and refine the EAM Workspace internship project.

## 7. Event Images

Some impressive photos recorded during the event at AWS Vietnam:

![FCAJ Community Day - Agentic AI Showcase](/images/4-EventParticipated/4.4-Event4/fcaj-community-day-1.jpg)

![FCAJ Community Day - Agentic AI Showcase](/images/4-EventParticipated/4.4-Event4/fcaj-community-day-2.jpg)

![FCAJ Community Day - Agentic AI Showcase](/images/4-EventParticipated/4.4-Event4/fcaj-community-day-3.jpg)

![FCAJ Community Day - Agentic AI Showcase](/images/4-EventParticipated/4.4-Event4/fcaj-community-day-4.jpg)
