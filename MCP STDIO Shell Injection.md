---
type: research-note
status: open
severity: critical
topic: llm-application-security
created: 2026-07-13
tags: [mcp-security, shell-injection, enterprise-ai, agent-infrastructure]
---

# MCP STDIO Shell Injection

## What Happened
**OX Security** discovered a command execution vulnerability in Anthropic's official **Model Context Protocol SDKs** in **April 2026**. STDIO transport passes parameters directly to shell without sanitisation, affecting **200,000+ instances** across **150 million plus** package downloads.

## Why It Matters
- Systemic architectural flaw in foundational AI infrastructure.
- Enables arbitrary code execution through MCP server configuration.
- Massive blast radius across enterprise AI agent deployments.

## Source
- Cloud Security Alliance Research Note - MCP Security Crisis 2026

## Related
- [[AI Security Index]]
- [[AI Red Teaming]]
- [[New MCP Spec Security Implications]]
- [[Prompt Injection]]
