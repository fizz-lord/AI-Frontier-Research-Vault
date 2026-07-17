---
type: research-note
status: open
severity: high
topic: llm-application-security
created: 2026-07-17
tags: [prompt-injection, ids, agent-security, statistical-detection]
---

# Prompt-Injection-Resistant IDS Detection Layer

## What Happened
Aaron Phifer added a behavioural detection layer to Triagewall, a self-hosted IDS alert triage tool. The layer applies **statistical process control** per host using `alert_rate` and `novel_sid` derived from raw Suricata alerts, with attacker-controllable fields base64-wrapped before LLM input.

## Why It Matters
- Because detection depends on numeric aggregates, not alert text, prompt injection has no vector on those fields.
- Suggests a general defensive pattern for AI-assisted security tooling: convert raw textual input into bounded numeric or boolean values before any model sees it.
- Directly measurable; reduces AI triage false positives while closing one injection pathway.

## Source
- triagewall.io - Behavioural Baselining

## Related
- [[AI Security Index]]
- [[Prompt Injection]]
- [[Autonomous LLM Vulnerability Hunting]]
