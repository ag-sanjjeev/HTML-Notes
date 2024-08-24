## &#9873; Base Tag
This `<base>` tag is used to represent the base URL for the all relative URLs present in the document.  

*There can be only one base URL for the current document. The base tag may has either `href=""` or `target=""` or both in their attributes.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<base>` tag created as, 
```xml
<head>
	<base href="{{URL/Location}}">
</head>
```

### &#10022; Attributes and Properties:
The base tag does not support any of the standard attributes and properties.
But supports only below attributes:
1. **href** - It specifies base URL/Location for the all other relative URLs.
2. **target** - It decides where to open each relative URLs.

### &#10022; Event Attributes:
The base tag does not support any of the event attributes.

### &#10022; Examples:
> Example for `<base>` tag
```xml
<head>
	<base href="https://www.examplesitedomain.com/">
</head>
<body>
	<img src="images/logo.png">
	<a href="pages/home.html">Home Page</a>
</body>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/base-tag.html)

---
[&#8682; To Top](#-base-tag)

[&#10094; Previous Topic](./b-tag.md) &emsp; [Next Topic &#10095;](./bdi-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
