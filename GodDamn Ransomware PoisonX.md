---
type: research-note
status: open
severity: critical
topic: ransomware
created: 2026-07-17
tags: [ransomware, edr-bypass, kernel, microsoft]
---

# GodDamn Ransomware and PoisonX Kernel Driver

## What Happened
Researchers documented the first ransomware case using a **legitimately Microsoft signed kernel driver** to terminate EDR processes from Ring 0 before encryption. The signed driver, **PoisonX**, allowed kernel-level EDR bypass without triggering code signature alerts.

## Why It Matters
- Raises the bar significantly for EDR detection and signed-driver trust.
- A Ring 0 kill chain step becomes accessible to ransomware operators if code signing abuse is not detected.
- Reinforces need for policy driven driver allowlisting and behavioural kernel monitoring.

## Source
- Infosecurity Magazine

## Related
- [[AI Security Index]]
- [[AI Red Teaming]]
- [[JadePuffer Autonomous Ransomware]]
