## &#9873; Area Tag
This `<area>` tag is used to define an area inside an image map. Which has predefined clickable areas.

*Image map allows geometric areas on it. Which associated with links.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<area>` tag created as, 
```xml
<img src="{{map image file}}" usemap="#{{name-of-the-map}}">
<map name="name-of-the-map">
	<area shape="{{shape-type}}" coords="{{co-ordinate-values}}" href="{{url/location}}">
</map>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **coords** - It specifies co-ordination of the area.
2. **shape** - It specifies shape of the clickable area. such as default or rect or circle or poly.
3. **href** - It specifies URL/Location to link.
4. **hreflang** - It specifies the language of the linked page/section.
5. **target** - It decides where to open the link.
6. **media** - It specifies what type of media/device that page/section optimized.
7. **download** - It will download the target file when user clicks.
8. **type** - It specifies which media type of the document or page linked. 
9. **rel** - It specifies relationship between the current document and the linked document.
10. **referrerpolicy** - It sent referrer information with the link.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<area>` tag
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
See this [`Code Reference`](../code/area-tag.html)

---
[&#8682; To Top](#-area-tag)

[&#10094; Previous Topic](./address-tag.md) &emsp; [Next Topic &#10095;](./article-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
