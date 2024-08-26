## &#9873; Definition Element Tag
This `<dfn>` tag is used to specify the term, which is defined by the content in HTML element.

*This `<dfn>` tag contains term. The immediate parent of `<dfn>` holds definition for the term.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<dfn>` tag created as, 
```xml
< ... >
<dfn>{{Term}}</dfn>
{{ definition for the term }}
</ ... >
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<dfn>` tag
```xml
<p>
	<dfn>CPU</dfn>
	is the main part of the computer.
</p>
```

> Example for `<dfn>` tag with title attribute
```xml
<p>
	<dfn title="Central Processing Unit">CPU</dfn>
	is the main part of the computer.
</p>
```
> Example for `<dfn>` tag with `<abbr>` tag
```xml
<p>
	<dfn><abbr title="Central Processing Unit">CPU</abbr></dfn>
	is the main part of the computer.
</p>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/dfn-tag.html)

---
[&#8682; To Top](#-definition-element-tag)

[&#10094; Previous Topic](./details-tag.md) &emsp; [Next Topic &#10095;](./dialog-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
