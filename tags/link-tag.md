## &#9873; Link Tag
This `<link>` tag is used to add external resources to the current HTML document.

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<link>` tag created as, 
```xml
<link rel="{{relationship-type}}" type="{{type-of-content}}" href="{{URL/Location}}">
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **rel** - It specifies relationship between the current document and the linked resource.
2. **type** - It specifies media type of the linked resource.
3. **href** - It specifies URL/Location to link.
4. **hreflang** - It specifies the language of the linked resource.
5. **crossorigin** - It determines the way of the request to the external resource for cross-origin access. 
6. **media** - It specifies the external resource to be used on which devices.
7. **referrerpolicy** - It specifies referrer information to send when fetching external resources.
8. **title** - It specifies an alternate stylesheet.
9. **sizes** - It specifies sizes of the linked resources as `HeightxWidth` or `any` sizes to apply, which is only for `rel="icon"`.


### &#10022; Event Attributes:
This tag does not support any of the event attributes.

### &#10022; Examples:
> Example for `<link>` tag 
```xml
<head>
	<link rel="stylesheet" type="text/css" href="main.css" />
</head>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/link-tag.html)

---
[&#8682; To Top](#-link-tag)

[&#10094; Previous Topic](./li-tag.md) &emsp; [Next Topic &#10095;](./main-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
