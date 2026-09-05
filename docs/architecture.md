# Lab Architecture

## Objective
Design an isolated Raspberry Pi-based T-Pot honeypot environment that can collect useful attack telemetry while reducing risk to other devices on the network.

## High-Level Design

```text
Internet
   |
[Router / Firewall]
   |
[Isolated Honeypot Segment]
   |
[Raspberry Pi + T-Pot]
   |
[Honeypot Telemetry / Dashboards]
   |
[Analyst Review]
```

## Security Design Principles
- Keep the honeypot separated from trusted personal or production devices.
- Do not store credentials, sensitive documents, or personal data on the honeypot.
- Restrict management access.
- Keep the host and supporting software patched.
- Treat all collected files and payloads as potentially malicious.
- Sanitize logs and screenshots before publishing them publicly.

## Hardware / Network Details
Replace the placeholders below with the real lab configuration.

| Component | Configuration |
|---|---|
| Raspberry Pi model | TODO |
| RAM | TODO |
| Storage | TODO |
| Network connection | TODO |
| Router/firewall | TODO |
| Network isolation method | TODO |
| T-Pot version | TODO |

## Data Flow
1. External traffic reaches only the intentionally exposed honeypot services.
2. T-Pot components capture security telemetry.
3. Logs/events are presented through the available monitoring interfaces.
4. Events are reviewed for attacker behavior, targeted services, and patterns.
5. Only sanitized findings are published in this repository.

## Portfolio Evidence
Add a sanitized architecture diagram to `diagrams/` after documenting the exact network topology.
