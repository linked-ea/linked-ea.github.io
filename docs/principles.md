---
layout: default
title: Principles & Rules
nav_order: 2
has_children: false
---

## Initiative Guiding Principles
{: .no_toc }

* Develop a set of proof-of-concept specifications, best practices, and implementations to link enterprise architecture models
* Leverage Archimate® modeling language - it is the most prevalent across EA practitioner community
* It is conformant with  [ArchiMate 3.2 Conformance documents](https://pubs.opengroup.org/architecture/archimate3-doc/ch-Introduction.html#sec-Conformance)[^1]
* It will not re-invent the wheel - leverage existing standards and approaches
* Decoupled from existing commercial product - based on Open Source technologies to allow unrestricted usage and architecture information exchange

## Definitions
* **Self-Sufficient Model** - An architecture model which does not have any external dependencies.
* **Provider Model** - An architecture model which is referred by consumer models. It may also be a Self-Sufficient Model.
* **Consumer Model** - An architecture model which refers and utilizes resources from Provider Models.
* **Resource** - All classes of architecture information possibly available in an architecture model, such as "Profiles", "Viewpoints", etc.
* **Concepts** - A subset of resource classes, core of architecture modeling, limited to "Elements", "Relationships", and "Relationship Connectors".

## Design Principles
* **Extensibility by addition** - consumer models may enrich resources and concepts from provider models.

## Rules
* **Consumer Models shall not consume from indirect Provider Models** - consumer models shall not consume resources from provider models not directly referenced by it. If necessary, a direct reference must be created.
* **Idempotency** - the methods to change content of a Model Store should be idempotent in a similar fashion to HTTP methods.


## Terminology

For the purposes of this project, the following terminology definitions apply:

* **Can** - Describes a possible feature or behavior available to the user.
* **Deprecated** - Items identified as deprecated may be removed in the next version of this standard.
* **Implementation** - Describes a value or behavior that is not defined by this standard but is selected by an implementor of a software tool. The value or behavior may vary among implementations that conform to this standard. A user should not rely on the existence of the value or behavior. The implementor shall document such a value or behavior so that it can be used correctly by a user.
* **May** - Describes a feature or behavior that is optional. To avoid ambiguity, the opposite of “may” is expressed as “need not”, instead of “may not”.
* **Obsolescent** - Certain features are obsolescent, which means that they may be considered for withdrawal in future versions of this standard. They are retained because of their widespread use, but their use is discouraged.
* **Shall** - Describes a feature or behavior that is a requirement. To avoid ambiguity, do not use “must” as an alternative to “shall”.
* **Shall not** - Describes a feature or behavior that is an absolute prohibition.
* **Should** - Describes a feature or behavior that is recommended but not required.
* **Will** - Same meaning as “shall”; “shall” is the preferred term.

[^1]: [ArchiMate®](https://www.opengroup.org/archimate-forum/archimate-overview)