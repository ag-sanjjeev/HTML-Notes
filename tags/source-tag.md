## &#9873; Source Tag
This `<source>` tag is used to specifies the multiple media sources for the HTML elements such [`<picture>`](./picture-tag.md), [`<audio>`](./audio-tag.md) and [`<video>`](./video-tag.md).

*This will be useful to add same media content in different format to provide compatibility for various browsers and systems.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<source>` tag created as, 
```xml
<source src="{{URL/Location}}" type="{{media-type}}">
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **src** - It specifies URL/Location for the external content.
2. **srcset** - It specifies a list of URLs/Locations for source files when type of source to be image or picture to use in different situations.
3. **type** - It specifies which (MIME) media type of the source linked.
4. **media** - It specifies media query that would be defined in a CSS.
5. **sizes** - It specifies image sizes for different page layouts.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<source>` tag 
```xml
<video>
	<source src="videos/company-documentary.webm" type="video/webm">
	<source src="videos/company-documentary.mp4" type="video/mp4">
	<source src="videos/company-documentary.avi" type="video/x-msvideo">	
</video>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/source-tag.html)

---
[&#8682; To Top](#-source-tag)

[&#10094; Previous Topic](./small-tag.md) &emsp; [Next Topic &#10095;](./span-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
