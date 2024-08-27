## &#9873; Object Tag
This `<object>` tag is used to specifies the external resource to implement in the current HTML document.

*This is useful to embed images, another browsing content, browser plug-ins, resources handled by browser plug-ins. This can run/display Java applets, Flash movies, ActiveX controls, maps, scan for viruses and verifies bank id.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<object>` tag created as, 
```xml
<object data="{{URL/Location}}"></object>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **name** - It specifies the name for the object.
2. **typemustmatch** - It specifies the `type` attribute and actual resource content must match.
3. **usemap** - It specifies the name of the image map to be used with object.
4. **form** - It specifies the object belongs to the form id.
5. **type** - It specifies the type of the media specified in the `data` attribute.
6. **data** - It specifies the URL/Location of the resource to be used by the object.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<object>` tag
```xml
<object data="images/flower.jpeg"></object>
```

### &#10022; Code Reference:

See this [`Code Reference`](../code/object-tag.html)

---
[&#8682; To Top](#-object-tag)

[&#10094; Previous Topic](./noscript-tag.md) &emsp; [Next Topic &#10095;](./ol-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
