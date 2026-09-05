# Honeypot Attack Analysis

This document is a repeatable SOC-style template for analyzing real telemetry collected by the lab. Do not add fabricated statistics.

## Observation Window
- Start: TODO
- End: TODO
- Total observation time: TODO

## Executive Summary
TODO: Summarize the most important activity observed during the collection period.

## Top Targeted Services
| Service / Port | Event Count | Notes |
|---|---:|---|
| TODO | TODO | TODO |

## Source Activity
Document only sanitized or appropriately aggregated information.

| Indicator / Category | Observation |
|---|---|
| Top source countries/regions | TODO |
| Top source ASNs/providers | TODO |
| Repeated source behavior | TODO |
| Scanning patterns | TODO |

## Notable Event Investigation
### Event ID: TODO
**Time:** TODO  
**Targeted service:** TODO  
**Observed behavior:** TODO  
**Indicators:** TODO  
**Analyst assessment:** TODO  
**Defensive recommendation:** TODO

## MITRE ATT&CK Mapping
Only map techniques when the observed evidence supports the mapping.

| Observed Behavior | ATT&CK Technique | Evidence |
|---|---|---|
| TODO | TODO | TODO |

## Lessons for a SOC Analyst
- What made the activity suspicious?
- Which logs were most useful?
- What additional telemetry would improve confidence?
- How would this activity be detected in an enterprise SIEM/EDR environment?
- What containment or prevention controls would be appropriate?
