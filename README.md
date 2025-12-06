# DASSH Homeland Security Design Challenge 2025  
### AI-Driven Log Analysis & Automated Incident Response System  
**Team:** CyberLions  
**Role:** Security Engineer / AI Systems Designer  
**Recognition:** National DHS Competition Participant (Feb 28 – Mar 2, 2025)

---

## Overview  
The **Designing Actionable Solutions for a Secure Homeland (DASSH)** Challenge is a national, DHS-backed competition focused on developing innovative approaches to “Security in an AI World.”  
The 2025 event included **160 students from 15 universities**, forming **37 teams** who developed solutions under the mentorship of homeland security experts.

This repository contains my team's submission:  
An **AI-driven log analysis and automated incident response prototype** designed to reduce alert fatigue, accelerate SOC operations, and demonstrate how LLMs can augment DHS workflows.

---

## Competition Problem Statements  
Teams were challenged to address one of three Homeland Security–driven problem areas:

1. **Building broader comfort with AI** for DHS personnel and society.  
2. **Using LLMs to improve DHS operations**, especially labor-intensive tasks.  
3. **Mitigating AI-enabled attacks** on critical infrastructure.

Our solution targeted **Problem Statement #2**:  
> *How can DHS use AI—specifically Large Language Models—to improve operations requiring significant personnel time?*

---

## Project Summary  
We developed a prototype system that automates early-stage SOC triage, reduces false positives, and enables faster, more reliable decision-making using AI-assisted log parsing.

### Key Features  
- **LLM-Based Log Parsing:** Automated classification, summarization, and severity scoring of raw security logs.  
- **Wazuh-Style Rule Correlation:** Multi-layer rule engine inspired by Wazuh to detect patterns across heterogeneous log streams.  
- **Noise Reduction Module:** Reduced alert volume and false positives by **60–70%**, improving analyst focus.  
- **Python Automation Scripts:** Triggered simulated containment actions (IP block, quarantine, escalation).  
- **Real-Time Response:** Reduced manual triage time from minutes to seconds.  
- **Explainable Output:** Human-readable insights to increase trust and comfort with AI in operational environments.

---

## Technical Architecture  

### Components  
- **LLM Engine:** GPT-based and open-source Llama models  
- **Rule Engine:** Wazuh-inspired correlation logic  
- **Automation Layer:** Python scripts for simulated incident response  
- **Supported Logs:** `auth.log`, system logs, Windows event logs, Wazuh alerts

---

## Core Capabilities  
| Capability | Description |
|-----------|-------------|
| Log Parsing | Converts raw logs to structured events using LLMs |
| Threat Correlation | Detects related attacks across multiple services |
| False-Positive Reduction | Achieved **60–70% reduction** in noise |
| Automated Response | Simulated containment within seconds |
| Executive Summary | Auto-generated IR notes for leadership briefings |

---

## Tools & Technologies  
- **Python 3.x**  
- **GPT / Llama LLMs**  
- **Prompt Engineering**  
- **Wazuh (conceptual inspiration)**  
- **Elastic-style event processing**  
- **JSON log pipelines**  

---

## Competition Background  
The challenge was hosted by **DHS Science & Technology Directorate**, **SENTRY**, and **CAOE**, with keynote remarks by:

- **Julie Brewer** – Acting Under Secretary for DHS S&T  
- **Chris Kraft** – Deputy CTO for AI at DHS  

Mentors included prior DASSH winners and Homeland Security experts, offering operational insight into AI deployment in real-world security missions.

Teams were judged on:

- Innovation  
- Feasibility  
- Operational value  
- Impact  

---


## Future Work  
- Add modular plugin support for new log types  
- Deploy as a lightweight SOC assistant CLI tool  
- Integrate RAG-based knowledge for enriched threat context  
- Containerize the pipeline (Docker/Kubernetes)

---

## Contact  
**Tanishka Mali**  
Cybersecurity Researcher & Graduate Student  
GitHub: https://github.com/tanishkamali14  
LinkedIn: https://linkedin.com/in/tanishkamali  

---

> *This prototype demonstrates how AI can augment national security operations by accelerating incident response and reducing analyst workload, supporting DHS’s vision for operational AI adoption.*


