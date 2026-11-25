---
tag: tier-routing
author: jay-flowers
category: gotcha
created_at: 2026-11-25T21:23:42Z
identity: tier-routing-20261125T212342-jay-flowers
tier: draft
as_of: "website@9c1acc4c5b81f57eae1a8400c8b43c296f318590"
---

The tier-routing skill's trigger is branch-state (ON_MAIN or UNRECOGNIZED_BRANCH), not "no spec exists" — tier-named branches missing their artifacts are committed intent and stay a STOP, never routed around. Any doc restating the trigger must carry this nuance or it overstates /uf.unleash's automation.
