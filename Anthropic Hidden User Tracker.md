---
type: research-note
status: open
severity: high
topic: privacy
created: 2026-07-09
tags: [privacy, surveillance, distillation, trust]
---

# Anthropic Hidden User Tracker in Claude Code

## What Happened
A security researcher discovered Anthropic deployed **prompt steganography** in Claude Code to secretly track Chinese users, recording timezone, proxy info, and suspected connections to Chinese AI labs. The code was hidden in plain sight using shorthand markers. Anthropic confirmed it was added as an **experiment** in **March 2026**.

## Why It Matters
- Despite its privacy focused public positioning, Anthropic implemented surveillance like tracking to combat model distillation.
- Undermines user trust and raises questions about whether similar hidden tracking exists elsewhere.
- Shows how U.S. and Chinese AI rivalry shapes product design and user experience.

## Source
- Ars Technica - Claude Secret Tracker Exposure

## Related
- [[AI Security Index]]
- [[AI Red Teaming]]
- [[Mirendil Self-Improving AI]]
