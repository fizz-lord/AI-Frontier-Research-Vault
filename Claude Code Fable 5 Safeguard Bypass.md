---
type: research-note
status: open
severity: high
topic: jailbreak
created: 2026-07-17
tags: [jailbreak, claude-code, safeguard-bypass, prompt-injection]
---

# Claude Code Fable 5 Safeguard Bypass via `/btw`

## What Happened
Security researcher Qi Deng publicly reproduced a **Fable 5 safeguard bypass** in **Claude Code** in July 2026. The trigger: appending `/btw` to prompts enabled broader cybersecurity use cases and caused guardrail failures that produced vulnerability exploitation code.

## Why It Matters
- Confirms frontier model safeguards remain brittle under trivial prompt conditioning.
- Makes repeated the Anthropic/Amazon government benchmark story: a single delimiter-style modifier bypasses model-level restrictions.
- `/btw` style tokens are simple enough to appear benign in review, making detection hard.
- Directly expands the jailbreak playbook for coding agents, not chat-only models.

## Source
- Qi Deng LinkedIn post, July 2026

## Related
- [[AI Security Index]]
- [[Jailbreak Techniques]]
- [[Prompt Injection]]
- [[US Jailbreak Benchmark]]
