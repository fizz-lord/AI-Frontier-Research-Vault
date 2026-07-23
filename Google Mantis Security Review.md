---
type: research-note
status: open
severity: high
topic: llm-application-security
created: 2026-07-23
tags: [llm-application-security, vulnerability-harness, google, open-source]
---

# Google Mantis Security Review Pipeline

## What Happened
**Google** released **Mantis**, a portable sequential toolkit of AI agent skills for automated security review pipelines. Its 15-stage pipeline covers threat modelling, vulnerability scanning, deduplication, false positive filtering, sandboxed crash reproduction, exploit chaining, and automated patching, designed to run in isolated Docker/gVisor containers.

## Why It Matters
- Mainstream platform provider productising end-to-end AI security review.
- Isolation by design reduces risk of agentic tools becoming attack vectors themselves.
- Adds to the growing list of production-grade open-source harnesses alongside Visa, Anthropic, and Alpha Omega offerings.

## Source
- tldrsec #338
- https://github.com/google/mantis

## Related
- [[AI Security Index]]
- [[AI Red Teaming]]
- [[Autonomous LLM Vulnerability Hunting]]
