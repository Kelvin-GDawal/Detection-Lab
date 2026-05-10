# Detection Lab

**Blue-Team Lab for Security Monitoring, Log Analysis, and Alert Investigation**

## Overview

This Detection Lab is a controlled cybersecurity environment built to practice security monitoring and investigation workflows. The lab is designed to generate test telemetry, ingest logs into a SIEM, review suspicious activity, and document findings in a format similar to a SOC investigation.

The goal of this project is not only to use security tools, but to show the full analyst process: environment setup, telemetry collection, alert review, evidence gathering, investigation notes, and lessons learned.

## Objectives

- Build a safe lab environment for practicing detection and analysis.
- Generate realistic security events and network activity for investigation.
- Ingest and review logs using SIEM concepts and structured analysis.
- Practice identifying suspicious patterns across host and network data.
- Document each investigation clearly enough for analyst handoff or portfolio review.

## Lab Scope

| Area | Description |
| --- | --- |
| Security Monitoring | Collecting and reviewing logs from lab systems and simulated activity |
| SIEM Analysis | Searching, filtering, and correlating events to understand suspicious behavior |
| Network Traffic Review | Using packet and protocol analysis to identify unusual connections or activity |
| Detection Engineering Practice | Translating observed behavior into repeatable detection ideas |
| Incident Documentation | Recording evidence, findings, impact, and recommended next steps |

## Tools Used

| Tool / Category | Purpose |
| --- | --- |
| SIEM Platform | Log ingestion, searching, alert review, and event correlation |
| Wireshark | Packet capture review and network protocol analysis |
| Windows Event Logs | Endpoint telemetry and host activity review |
| Attack Simulation / Test Activity | Generating safe telemetry for detection practice |
| Markdown | Writing clear investigation notes and portfolio documentation |

## Skills Demonstrated

- SIEM search and log analysis
- Network traffic analysis
- Alert triage and evidence collection
- Suspicious activity investigation
- Detection logic development
- Incident documentation and reporting
- Clear technical communication

## Lab Architecture

> Add a network diagram or screenshot here when available.

| Component | Role |
| --- | --- |
| Analyst Workstation | Used to review alerts, query logs, and document findings |
| Target / Test System | Generates endpoint activity and security events |
| SIEM / Logging Platform | Central location for log ingestion and investigation |
| Network Analysis Tooling | Captures or reviews network activity for suspicious behavior |

## Investigation Workflow

1. Generate controlled test activity in the lab.
2. Confirm that logs and network data are being collected.
3. Search the SIEM for relevant events, timestamps, hosts, users, IPs, and process activity.
4. Review supporting evidence with network or endpoint tools.
5. Determine whether the activity is benign, suspicious, or malicious.
6. Document the finding, evidence, and recommended response.
7. Identify detection improvements or follow-up questions.

## Detection Scenarios

| Scenario | Data Source | Analyst Focus | Status |
| --- | --- | --- | --- |
| Failed Login Review | Authentication logs | Identify repeated failures, source host, target account, and timeline | Planned |
| Suspicious Network Connection | Packet capture / network logs | Review destination, protocol, port, and traffic pattern | Planned |
| Malware-Like Test Activity | Endpoint logs | Review process activity, command execution, and related indicators | Planned |
| Privilege or Account Activity | Windows logs / SIEM | Identify account changes, privilege use, and suspicious timing | Planned |

## Evidence and Screenshots

Add screenshots as the lab develops. Each screenshot should include a short explanation of what it proves.

| Reference | Evidence | Notes |
| --- | --- | --- |
| Ref 1 | Lab architecture diagram | Shows the systems and data flow used in the lab |
| Ref 2 | SIEM log ingestion view | Confirms logs are being received and searchable |
| Ref 3 | Example alert or search query | Shows the detection or investigation starting point |
| Ref 4 | Investigation evidence | Shows supporting logs, packet data, or endpoint details |

## Investigation Report Template

Use this format for each detection case added to the lab:

```text
Title:
Date:
Scenario:
Data Sources:
Initial Alert or Lead:
Key Evidence:
Timeline:
Analysis:
Conclusion:
Recommended Response:
Lessons Learned:
Detection Improvements:
```

## Key Takeaways

- A useful detection lab should show both tool usage and analyst reasoning.
- Strong documentation makes an investigation easier to validate, repeat, and improve.
- Screenshots are most valuable when they support a clear finding, not when they only show that a tool was opened.
- Mapping activity from raw telemetry to a conclusion is the core skill this lab is designed to build.

## Next Improvements

- Add a lab architecture diagram.
- Add screenshots showing SIEM ingestion and sample searches.
- Document at least three completed detection scenarios.
- Include example queries, timelines, and analyst notes for each case.
- Add a short summary of what changed after each investigation.
