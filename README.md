# Ransomware-Sentinel-Detection-Hub
KQL detections, playbooks, and remediation guides to detect, investigate, and respond to ransomware campaigns (stages 1–8). Built for Microsoft Sentinel + EDR integrations.

Repository containing detection rules, investigation playbooks and remediation guidance to detect and respond to ransomware campaigns using Microsoft Sentinel and common EDR telemetry.

## Contents
- `kql/` : Kusto rules grouped by ransomware stage (suspicious execution, persistence, privilège escalation, defense evasion, reconnaissance, lateral movement, exfiltration, destructive actions)
- `playbooks/` : Automated response playbooks (Logic Apps / Power Automate examples)
- `docs/` : Remediation runbooks, false-positive guidance, MITRE mappings and mapping to detection stages

## Goals
1. Accelerate detection of ransomware TTPs across the kill chain.
2. Provide clear investigation steps and fast remediation actions.
3. Reduce false positives with tuned thresholds and exclusions.
