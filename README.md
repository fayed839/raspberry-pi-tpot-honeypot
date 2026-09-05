# Raspberry Pi T-Pot Honeypot

## Project Overview
This project documents my hands-on deployment of a **T-Pot honeypot environment on Raspberry Pi** for defensive security research, attack telemetry collection, and blue-team analysis.

The goal is to demonstrate practical experience with honeypot monitoring, Linux administration, network security, log analysis, threat intelligence, attacker-behavior analysis, and SOC-style investigation.

> **Ethics & Safety:** This repository is for authorized defensive security research only. Sensitive data, credentials, private IP addresses, and personally identifiable information should never be committed.

## Architecture

```text
Internet
   |
Router / Firewall
   |
Isolated Honeypot Network
   |
Raspberry Pi running T-Pot
   |
Honeypot Services + Logging + Dashboards
   |
Security Analysis / Reporting
```

See [`docs/architecture.md`](docs/architecture.md) for documentation.

## Skills Demonstrated
- Raspberry Pi / Linux administration
- Honeypot deployment and monitoring
- Network security monitoring
- Security event and log analysis
- Threat intelligence enrichment
- Incident investigation and documentation
- Blue-team / SOC workflows

## Repository Structure

```text
.
├── README.md
├── docs/
│   ├── architecture.md
│   ├── deployment.md
│   ├── attack-analysis.md
│   ├── lessons-learned.md
│   └── security-and-privacy.md
├── sample-data/
├── screenshots/
└── diagrams/
```

## Project Workflow
1. Prepare and harden the Raspberry Pi host.
2. Place the honeypot in an isolated network segment.
3. Deploy and validate T-Pot components.
4. Confirm telemetry and dashboard visibility.
5. Collect attack data during a controlled observation period.
6. Analyze connection patterns, ports, source IPs, and attacker behavior.
7. Document findings and defensive lessons.
8. Sanitize all screenshots and logs before publishing.

## Evidence to Add
This repository intentionally avoids inventing results. I will add real evidence from my lab, including sanitized dashboard screenshots, attacked ports/services, attack-source summaries, sample events, notable activity timelines, and hardware/setup photos.

## Resume-Ready Summary
**Raspberry Pi T-Pot Honeypot Lab** — Deployed and monitored a Raspberry Pi-based T-Pot honeypot environment to collect and analyze malicious network activity. Reviewed attack telemetry, targeted services, source activity, and security events while documenting findings using a SOC-style workflow.

## Status
**Portfolio documentation in progress.**

### Planned Improvements
- Add sanitized attack telemetry
- Add architecture diagram
- Add project screenshots
- Add threat-analysis summaries
- Add MITRE ATT&CK mappings where supported by observed evidence
