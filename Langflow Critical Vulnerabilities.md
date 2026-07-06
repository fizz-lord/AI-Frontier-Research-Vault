---
type: research-note
status: open
severity: high
topic: llm-application-security
created: 2026-07-03
tags: [llm-application-security, langflow, auth-bypass, code-execution]
---

# Langflow Critical Vulnerabilities

## What Happened
IBM security researchers found six serious vulnerabilities in **Langflow OSS**.

## Why It Matters
- One bug allows strangers to run code outright.
- Others allow authentication bypass, key reuse, and data theft.
- Low-code/visual AI tooling widens the exposed user base.

## Notes
- Review exposed Langflow deployments
- Prioritise auth boundary and key isolation checks

## Related
- [[AI Security Index]]
- [[AI Red Teaming]]
- [[Prompt Injection]]
