## &#9873; Template Tag
This `<template>` tag is used to specifies the group of elements to be reused.

*This `<template>` element will not be rendered when page loads. But it can be rendered with the help of JavaScript.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<template>` tag created as, 
```xml
<template>
	...
</template>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).

### &#10022; Event Attributes:
This does not support any of the event attributes.

### &#10022; Examples:
> Example for `<template>` tag
```xml
<template>
	<h3>Fruits</h3>
	<img src="">
	<a href="" download>Download the image</a>
</template>

<script type="text/javascript">
	function showImages() {
		let templateElement = document.getElementsByTagName('template')[0];
		let clone = templateElement.content.cloneNode(true);	
		clone.querySelector('a').href = 'fruits-image1.html'
		clone.querySelector('img').src = 'fruits-image1.html'
		document.body.appendChild(clone);			
	}
</script>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/template-tag.html)

---
[&#8682; To Top](#-template-tag)

[&#10094; Previous Topic](./td-tag.md) &emsp; [Next Topic &#10095;](./textarea-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
