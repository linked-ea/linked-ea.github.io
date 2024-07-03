---
layout: default
title: Element
parent: Model Resources
nav_order: 6
---

# Element
{: .no_toc }

Alpha Release
{: .label .label-yellow }

The resource is aligned with [ArchiMate® 3.2 Specification](https://pubs.opengroup.org/architecture/archimate3-doc/index.html) and is semantically compatible with Element concept part of [ArchiMate® 3.2 Language Structure](https://pubs.opengroup.org/architecture/archimate3-doc/ch-Language-Structure.html).

## Features

| Feature         | Requirement         | Description |
|:----------------|:--------------------|:------------|
| properties      | Optional            |             |
| imageRef        | Optional            | Reference to image within the model or referenced model to be rendered in views replacing the default iconography of the [ArchiMate®] language |

## Example
```ts
	// Typescript code

	import { CORE.ELEMENT } from '@linked-ea/core-typescript'

	const element: CORE.Element = {
		model: "xxx",
		identifier: "xxx",
		info: {
			type: "xx"
			viewRef: "http://viewref"
		}
	}
```

[ArchiMate®]: https://www.opengroup.org/archimate-forum/archimate-overview