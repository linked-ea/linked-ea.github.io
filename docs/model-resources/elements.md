---
layout: default
title: Element
parent: Model Resources
nav_order: 6
---

# Element
{: .no_toc }

The resource aligned with [ArchiMate® 3.2 Specification](https://pubs.opengroup.org/architecture/archimate3-doc/index.html) and is semantically compatible with Element concept part of [ArchiMate® 3.2 Language Structure](https://pubs.opengroup.org/architecture/archimate3-doc/ch-Language-Structure.html).

## Features

| Feature         | Requirement         |
|:----------------|:--------------------|
| Name            | Mandatory           |
| Documentation   | Optional            |
| Properties      | Optional            |



## Example
```ts
	// Typescript code

	import { CORE.ELEMENT } from '@linked-ea/core-typescript'

	const element: CORE.Element = {
		model: "xxx",
		identifier: "xxx",
		info: {
			type: "xx"
		}
	}
```