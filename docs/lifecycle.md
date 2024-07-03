---
layout: default
title: Lifecycle
nav_order: 4
---

# Lifecycle
{: .no_toc }

The lifecycle of a model must take special considerations on how they are published and consumed by other models to prevent introduction of data integrity issues.

![](../../assets/images/lifecycle.svg)

## Deprecation

All resource classes in this specification contain an intrinsic property that indicates they are [deprecated], and [may] be removed in the next publication of the model.

The removal of a resource from a published model [shall] take place in two steps:
1. Initially deprecate resource and publish model, allow consumer to react to deprecation and future removal
2. Remove deprecated resources and publish model



[Can]: docs/principles.html#terminology
[can]: docs/principles.html#terminology
[Deprecated]: docs/principles.html#terminology
[deprecated]: docs/principles.html#terminology
[Implementation]: docs/principles.html#terminology
[implementation]: docs/principles.html#terminology
[May]: docs/principles.html#terminology
[may]: docs/principles.html#terminology
[Obsolescent]: docs/principles.html#terminology
[obsolescent]: docs/principles.html#terminology
[Shall]: docs/principles.html#terminology
[shall]: docs/principles.html#terminology
[Shall not]: docs/principles.html#terminology
[shall not]: docs/principles.html#terminology
[Should]: docs/principles.html#terminology
[should]: docs/principles.html#terminology
[Will]: docs/principles.html#terminology
[will]: docs/principles.html#terminology