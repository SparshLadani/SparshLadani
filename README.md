# Hi there! 👋

## 👨‍💻 Intro
I'm Sparsh Ladani — a recent Computer Science graduate from Dalhousie University with a Certificate in Cybersecurity, focused on **AppSec, security engineering, and AI/LLM security**. I like building things that test where the guardrails actually break, here's what I've worked on so far.

## 🤖 AI Security

### 1. [MCP Agent Red-Team Lab](https://github.com/SparshLadani/MCP-Agent-Red-Team-Lab)
Built a deliberately vulnerable MCP server, red-teamed it with an AI agent (Claude Code), and uncovered 5 vulnerability classes including path traversal, unauthenticated credential access, and a tool-chaining exfiltration flaw where the agent leaked a secret it had initially refused to hand over. Mapped every finding into a full threat model (assets, trust boundaries, mitigations).

### 2. Autonomous AI Threat Hunting Agent[Threat Hunting AI Agent](https://github.com/SparshLadani/Threat-Hunting-AI-Agent)
An agent built on LangGraph and the OpenAI API (GPT-4o-mini) that pulls from Elastic SIEM, detects APT-level behavior mapped to MITRE ATT&CK, and produces a SOC-ready report in under a minute. The interesting part was getting the agent to reason over alerts instead of just summarizing them.

### 3. Prompt Injection Detection Platform[Prompt Injection Detection Platform](https://github.com/SparshLadani/Prompt-Injection-Detection-Platform)
A cloud-native platform on AWS that classifies prompt injection attacks against MITRE ATLAS categories.

## 🛡️ AppSec & Security Engineering

### 4. Secure Code Review — Flask/PostgreSQL Expense Platform[Secure Code Review](https://github.com/SparshLadani/expense-guard)
Manually audited authentication, authorization, and business logic, identifying an IDOR, a JWT role-trust flaw, and a mass assignment vulnerability, documented as PR-ready remediation reports.

### 5. Serverless AWS CloudTrail Threat Detection Pipeline[AWS Cloud Trail Threat Detection Pipeline](https://github.com/SparshLadani/AWS-CloudTrail-Threat-Detection-Alerting-System)
A fully serverless setup on AWS that monitors CloudTrail logs and flags suspicious API activity. No servers to babysit, which was kind of the point.

### 6. WannaCry Ransomware Homelab Analysis[SOC-DFIR HomeLab](https://medium.com/bugbountywriteup/wannacry-ransomware-a-dfir-soc-monitoring-lab-walkthrough-9001f61a71e9)
Detonated WannaCry in an isolated homelab and dug into it with static and dynamic analysis, extracting IoCs and mapping behavior to MITRE ATT&CK. Also ran an adversary TTP emulation lab with Atomic Red Team, mapped to the Cyber Kill Chain.

## 💼 Experience
Cybersecurity Intern at **Thales** — hands-on with penetration testing, secure code review, network security architecture, and security monitoring.

## 🚀 Core Skills
Python, LangGraph, AI/LLM Security, Elastic SIEM, IBM QRadar, KQL, MITRE ATT&CK, Cyber Kill Chain, AWS Security, Docker, Secure Code Review, Nmap, Wireshark, Burp Suite, OWASP ZAP, Nessus.

## 🔒 Certifications
CompTIA Security+, Microsoft Azure Fundamentals (AZ-900), ISC2 CC.

## 🌀 Focus
I personally like working at the intersection of AppSec and AI system security.

## 📫 Let's Connect
Looking for full-time AppSec, Security Engineering, or AI Security roles. Always happy to talk security, AI, or new ideas — let's connect on [LinkedIn](https://www.linkedin.com/in/sparshladani/).
