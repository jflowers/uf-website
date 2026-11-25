---
tag: ci-gates
author: jay-flowers
category: gotcha
created_at: 2026-11-25T21:23:33Z
identity: ci-gates-20261125T212333-jay-flowers
tier: draft
as_of: "website@9c1acc4c5b81f57eae1a8400c8b43c296f318590"
---

"CI green" is a vacuous acceptance criterion for changes to CI workflow files whenever the workflow triggers only on the protected branch — the change cannot be exercised before merge. Before relying on a compensating control to justify removing a heavier gate, verify the control actually fires for the category it is claimed to cover.
