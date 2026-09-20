<div align="center">

```
 ██████╗ ███████╗ ██████╗██╗   ██╗██████╗ ███████╗    ██╗███╗   ██╗██╗████████╗
██╔════╝ ██╔════╝██╔════╝██║   ██║██╔══██╗██╔════╝    ██║████╗  ██║██║╚══██╔══╝
╚█████╗  █████╗  ██║     ██║   ██║██████╔╝█████╗      ██║██╔██╗ ██║██║   ██║   
 ╚═══██╗ ██╔══╝  ██║     ██║   ██║██╔══██╗██╔══╝      ██║██║╚██╗██║██║   ██║   
██████╔╝ ███████╗╚██████╗╚██████╔╝██║  ██║███████╗    ██║██║ ╚████║██║   ██║   
╚═════╝  ╚══════╝ ╚═════╝ ╚═════╝ ╚═╝  ╚═╝╚══════╝    ╚═╝╚═╝  ╚═══╝╚═╝   ╚═╝   
```

### `whoami`

# Sparsh Ladani

**`root@security`:** AppSec &bull; Security Engineering &bull; AI/LLM Security

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00FF41&center=true&vCenter=true&width=650&lines=Breaking+things+to+understand+them.;Red-teaming+AI+agents+before+they+ship.;Finding+the+bug+before+the+attacker+does.;Currently%3A+applying+for+Security+Engineering+roles." alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-000000?style=for-the-badge&logo=linkedin&logoColor=00FF41&labelColor=0d1117)](https://www.linkedin.com/in/sparshladani/)
![Status](https://img.shields.io/badge/status-open_to_work-00FF41?style=for-the-badge&labelColor=0d1117)

</div>

<br>

```diff
+ [INFO] Loading operator profile...
+ [INFO] Role: Recent CS Graduate, Dalhousie University | Certificate in Cybersecurity
+ [INFO] Specialization: AppSec / Security Engineering / AI-LLM Security
+ [INFO] Mission: Find where the guardrails actually break, before someone else does.
+ [OK]   Profile loaded successfully.
```

---

## `>_` About This Operator

```python
class SparshLadani:
    def __init__(self):
        self.role          = "Security Engineer / AppSec"
        self.education     = "B.CompSci + Certificate in Cybersecurity @ Dalhousie University"
        self.focus         = ["AppSec", "Security Engineering", "AI/LLM Security"]
        self.philosophy    = "Build it. Break it. Document exactly how it broke."

    def daily_loop(self):
        while True:
            self.recon()          # find the attack surface
            self.exploit()        # prove the risk is real, not theoretical
            self.report()         # write it up so someone can actually fix it
            yield "repeat"

    def whoami(self):
        return "I like building things that test where the guardrails actually break."
```

<br>

## `[ ./scan_targets.sh ]` &mdash; Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 AI Security

<details open>
<summary><b>🕸️ MCP Server Red-Teaming</b></summary>
<br>

![](https://img.shields.io/badge/target-MCP_Server-red?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/vulns_found-5-critical?style=flat-square&labelColor=0d1117&color=ff0055)

Built a deliberately vulnerable MCP server, red-teamed it with Claude Code as the attacking agent. Uncovered **path traversal**, **unauthenticated credential access**, and a **tool-chaining exfiltration flaw** where the agent leaked a secret it had initially refused to hand over. Full threat model delivered — assets, trust boundaries, mitigations.

`Python` `MCP` `AI Red-Teaming` `Threat Modeling`

[**→ inspect_repo**](https://github.com/SparshLadani/MCP-Agent-Red-Team-Lab)

</details>

<details open>
<summary><b>🎯 Autonomous Threat Hunting Agent</b></summary>
<br>

![](https://img.shields.io/badge/runtime-%3C60s-00FF41?style=flat-square&labelColor=0d1117)

An agent on **LangGraph + GPT-4o-mini** that pulls from Elastic SIEM, detects APT-level behavior mapped to **MITRE ATT&CK**, and produces a SOC-ready report in under a minute. The hard part: getting it to *reason* over alerts instead of just summarizing them.

`LangGraph` `OpenAI API` `Elastic SIEM` `MITRE ATT&CK`

[**→ inspect_repo**](https://github.com/SparshLadani/Threat-Hunting-AI-Agent)

</details>

<details open>
<summary><b>🧪 Prompt Injection Detection Platform</b></summary>
<br>

![](https://img.shields.io/badge/cloud-AWS-FF9900?style=flat-square&labelColor=0d1117)

Cloud-native platform on AWS that classifies prompt injection attacks against **MITRE ATLAS** categories.

`AWS` `MITRE ATLAS` `Cloud-Native`

[**→ inspect_repo**](https://github.com/SparshLadani/Prompt-Injection-Detection-Platform)

</details>

</td>
<td width="50%" valign="top">

### 🛡️ AppSec & Security Engineering

<details open>
<summary><b>🔍 Secure Code Review &mdash; Expense Platform</b></summary>
<br>

![](https://img.shields.io/badge/stack-Flask_/_PostgreSQL-333?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/findings-IDOR_·_JWT_·_Mass_Assignment-ff0055?style=flat-square&labelColor=0d1117)

Manually audited authentication, authorization, and business logic. Identified an **IDOR**, a **JWT role-trust flaw**, and a **mass assignment vulnerability** — documented as PR-ready remediation reports.

`Manual Code Review` `Flask` `PostgreSQL` `OWASP`

[**→ inspect_repo**](https://github.com/SparshLadani/expense-guard)

</details>

<details open>
<summary><b>☁️ CloudTrail Threat Detection Pipeline</b></summary>
<br>

![](https://img.shields.io/badge/architecture-serverless-00FF41?style=flat-square&labelColor=0d1117)

Fully serverless AWS pipeline that monitors CloudTrail logs and flags suspicious API activity. No servers to babysit — which was kind of the point.

`AWS Lambda` `CloudTrail` `Serverless`

[**→ inspect_repo**](https://github.com/SparshLadani/AWS-CloudTrail-Threat-Detection-Alerting-System)

</details>

<details open>
<summary><b>🦠 WannaCry Ransomware Homelab Analysis</b></summary>
<br>

![](https://img.shields.io/badge/env-isolated_homelab-red?style=flat-square&labelColor=0d1117)

Detonated WannaCry in an isolated homelab. Static + dynamic analysis, IoC extraction, behavior mapped to **MITRE ATT&CK**. Also ran an adversary TTP emulation lab with **Atomic Red Team**, mapped to the Cyber Kill Chain.

`Malware Analysis` `DFIR` `Atomic Red Team`

[**→ read_writeup**](https://medium.com/bugbountywriteup/wannacry-ransomware-a-dfir-soc-monitoring-lab-walkthrough-9001f61a71e9)

</details>

</td>
</tr>
</table>

---

## `[ ./cat experience.log ]`

```yaml
role:      Cybersecurity Intern
org:       Thales
scope:
  - penetration testing
  - secure code review
  - network security architecture
  - security monitoring
```

---

## `[ ./arsenal --list ]`

<div align="center">

**Languages & Core**

![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=00FF41)
![KQL](https://img.shields.io/badge/KQL-000000?style=for-the-badge&logo=microsoftazure&logoColor=00FF41)

**AI / Agent Security**

![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=for-the-badge&logoColor=00FF41)
![OpenAI](https://img.shields.io/badge/OpenAI_API-000000?style=for-the-badge&logo=openai&logoColor=00FF41)

**Detection & Threat Intel**

![Elastic](https://img.shields.io/badge/Elastic_SIEM-000000?style=for-the-badge&logo=elastic&logoColor=00FF41)
![QRadar](https://img.shields.io/badge/IBM_QRadar-000000?style=for-the-badge&logo=ibm&logoColor=00FF41)
![MITRE](https://img.shields.io/badge/MITRE_ATT%26CK-000000?style=for-the-badge&logoColor=00FF41)

**Offensive Security Tooling**

![Nmap](https://img.shields.io/badge/Nmap-000000?style=for-the-badge&logo=nmap&logoColor=00FF41)
![Wireshark](https://img.shields.io/badge/Wireshark-000000?style=for-the-badge&logo=wireshark&logoColor=00FF41)
![Burp](https://img.shields.io/badge/Burp_Suite-000000?style=for-the-badge&logoColor=00FF41)
![OWASP](https://img.shields.io/badge/OWASP_ZAP-000000?style=for-the-badge&logo=owasp&logoColor=00FF41)
![Nessus](https://img.shields.io/badge/Nessus-000000?style=for-the-badge&logoColor=00FF41)

**Cloud & Infra**

![AWS](https://img.shields.io/badge/AWS_Security-000000?style=for-the-badge&logo=amazonaws&logoColor=00FF41)
![Docker](https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=00FF41)

</div>

---

## `[ ./decrypt certifications.enc ]`

<div align="center">

| 🔐 Certification | Issuer |
|:---|:---:|
| **CompTIA Security+** | CompTIA |
| **Microsoft Azure Fundamentals (AZ-900)** | Microsoft |
| **ISC2 Certified in Cybersecurity (CC)** | ISC2 |

</div>

---

## `[ ./cat focus.txt ]`

```
I like working at the intersection of AppSec and AI system security —
where traditional secure-code-review discipline meets the new
attack surface that agents and LLMs introduce.
```

---

<div align="center">

### `[ ./connect --request ]`

Actively looking for full-time **AppSec**, **Security Engineering**, or **AI Security** roles.

[![LinkedIn](https://img.shields.io/badge/Let's_talk_security-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sparshladani/)

<br>

```diff
+ [OK] Connection request sent. Awaiting handshake...
```

<img src="https://komarev.com/ghpvc/?username=SparshLadani&color=00FF41&style=for-the-badge&label=INTRUDERS+DETECTED" alt="Profile Views">

</div>
