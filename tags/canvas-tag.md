## &#9873; Canvas Tag
This `<canvas>` tag is used to draw graphics on the current HTML document.

*This graphics can be drawn via scripts(usually JavaScript). Either the canvas scripting API or the WebGL API to draw graphics and animations.* 

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<canvas>` tag created as, 
```xml
<canvas id="{{id_name}}"></canvas>
<script type="text/javascript">
	...
</script>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<canvas>` tag
```xml
<canvas id="myGraphics"></canvas>
<script type="text/javascript">
	let myGraphics = document.getElementById('myGraphics');
	let context = myGraphics.getContext('2d');

	context.fillStyle = '#000000';
	context.fillRect(10, 10, 60, 60);
</script>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/canvas-tag.html)\
\
See this [`HTML Canvas Reference`](https://github.com/ag-sanjjeev/HTML-Canvas-Reference)

---
[&#8682; To Top](#-canvas-tag)

[&#10094; Previous Topic](./button-tag.md) &emsp; [Next Topic &#10095;](./caption-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
