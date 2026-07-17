---
type: research-note
status: open
severity: high
topic: autonomous-red-team
created: 2026-07-17
tags: [autonomous-red-team, bug-bounty, llm-offensive, agentic-ai]
---

# Autonomous Hackbot Finds 126 Vulnerabilities in Bug Bounties

## What Happened
Joseph Thacker and JD built a part time autonomous hackbot using **Claude Code** skills for recon, fuzzing, and deep application analysis, with an orchestrator improving target selection and a validation bot reducing false positives from 80% to 60%. Over five months it found **126 vulnerabilities**, including an unauthenticated Western Union customer PII leak, a stored XSS on Raydium, and Google API key escalation to Super Admin over roughly 60,000 users.

## Why It Matters
- First public account of a net profitable autonomous bug bounty workflow running alongside human work.
- The critical engineering choices were persistence through real browser auth, model routing by task cost, and validation only models.
- Demonstrates that frontier coding agents can discover and chain real world critical vulnerabilities at bug bounty scale.

## Source
- josephthacker.com - We Built a Hackbot, 1 July 2026

## Related
- [[AI Security Index]]
- [[AI Red Teaming]]
- [[Autonomous LLM Vulnerability Hunting]]
- [[JadePuffer Autonomous Ransomware]]
