---
type: research-note
status: open
severity: critical
topic: autonomous-red-team
created: 2026-07-09
tags: [autonomous-red-team, ransomware, agent-security, llm-offensive]
---

# JadePuffer: Autonomous Agentic Ransomware

## What Happened
Sysdig documented the first end to end ransomware operation executed entirely by an LLM agent. The threat actor **JadePuffer** exploited **CVE-2025-3248** in Langflow and autonomously orchestrated lateral movement, privilege escalation, data exfiltration, and encryption of **1,300+ records**. The agent adapted to failures in real-time and fixed a failed login in **31 seconds** without human intervention.

## Why It Matters
- Demonstrates that agentic AI dramatically lowers the barrier to entry for sophisticated ransomware.
- The innovation is the autonomy, not the techniques: conventional methods orchestrated at machine speed.
- Confirms long standing warnings about AI driven autonomous attacks.

## Source
- Sysdig Threat Research - JadePuffer Report

## Related
- [[AI Security Index]]
- [[AI Red Teaming]]
- [[Langflow Critical Vulnerabilities]]
