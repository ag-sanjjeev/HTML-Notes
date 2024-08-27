## &#9873; Map Tag
This `<map>` tag is used to define an image map. Which has clickable areas on an image.

*Image map allows geometric areas on it. Which associated with click-able areas.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<map>` tag created as, 
```xml
<img src="{{map image file}}" usemap="#{{name-of-the-map}}">
<map name="name-of-the-map">
	<area shape="{{shape-type}}" coords="{{co-ordinate-values}}" href="{{url/location}}">
</map>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **name** - It specifies the name of the map.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<map>` tag
```xml
<img src="worldmap.png" usemap="#worldmap">
<map name="worldmap">
	<area shape="poly" coords="...,...,...,...." href="Africa.html">
	<area shape="poly" coords="...,...,...,...." href="Antarctica.html">
	<area shape="poly" coords="...,...,...,...." href="Asia.html">
	<area shape="poly" coords="...,...,...,...." href="Australia.html">
	<area shape="poly" coords="...,...,...,...." href="Europe.html">
	<area shape="poly" coords="...,...,...,...." href="North America.html">
	<area shape="poly" coords="...,...,...,...." href="South America.html">
</map>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/map-tag.html)

---
[&#8682; To Top](#-map-tag)

[&#10094; Previous Topic](./main-tag.md) &emsp; [Next Topic &#10095;](./mark-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
