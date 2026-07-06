---
type: research-note
status: open
severity: high
topic: identity-attacks
created: 2026-07-03
tags: [identity-attacks, oauth, gmail, token-hijack]
---

# ToddyCat OAuth Token Gmail Theft

## What Happened
**ToddyCat** began stealing Gmail access by hijacking signed in browser sessions and reusing **OAuth tokens** instead of passwords.

## Why It Matters
- Token based sessions bypass password controls.
- Gmail access gives historical mail, contacts, reset flows, and linked services.
- OAuth token theft is increasingly common against corporate identities.

## Notes
- Treat tokens as credentials
- Reuse and scope token handling carefully

## Related
- [[AI Security Index]]
- [[AI Red Teaming]]
