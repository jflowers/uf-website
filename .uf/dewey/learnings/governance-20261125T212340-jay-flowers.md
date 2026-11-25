---
tag: governance
author: jay-flowers
category: pattern
created_at: 2026-11-25T21:23:40Z
identity: governance-20261125T212340-jay-flowers
tier: draft
as_of: "website@9c1acc4c5b81f57eae1a8400c8b43c296f318590"
---

Rewriting a policy section in AGENTS.md is a graph-wide change, not a section-local one: every artifact that embeds or derives from the policy — sibling MUST sections (exempt lists, phase boundaries, branch conventions), verbatim templates in commands like uf.agent-brief.md, and scaffold injection logic like uf.init — must be updated in the same change window, or each stale copy becomes a competing governance voice for autonomous agents.
