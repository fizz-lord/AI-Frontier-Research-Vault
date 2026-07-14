---
type: research-note
status: open
severity: high
topic: attack-surface
created: 2026-07-09
tags: [attack-surface, ai-gateways, aws, identity]
---

# AI Gateways as High Privilege Targets

## What Happened
Darktrace researchers uncovered an attack on an AWS EC2 instance running **LiteLLM proxy** for Amazon Bedrock. The intrusion led to cryptomining but revealed the real risk: AI gateways concentrate model access, cloud IAM credentials, and identity and permission management in a single highly privileged system. Attackers could pivot to manipulate AI workflows, access sensitive data, or breach entire cloud environments.

## Why It Matters
- New architectural vulnerability class emerges as organisations centralise AI model access.
- Gateway breaches potentially grant attackers control over multiple models, cloud infrastructure, and identity systems simultaneously -- exponential blast radius.

## Source
- CSO Online - AI Gateway Security Risk

## Related
- [[AI Security Index]]
- [[AI Red Teaming]]
- [[Hidden Enterprise AI Agents]]
