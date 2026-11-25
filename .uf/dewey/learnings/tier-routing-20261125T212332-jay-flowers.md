---
tag: tier-routing
author: jay-flowers
category: gotcha
created_at: 2026-11-25T21:23:32Z
identity: tier-routing-20261125T212332-jay-flowers
tier: draft
as_of: "website@9c1acc4c5b81f57eae1a8400c8b43c296f318590"
---

When replacing an explicit must-spec list with scope-signal routing plus risk floors, diff the old list against the new floors category by category. Categories that drop out (e.g., agent prompts, CI workflow files, data schemas) are typically the small-diff/high-risk classes floors exist to catch — floors should be enumerated from the replaced list's security-bearing items, not only from classic vulnerability categories.
