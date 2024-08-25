## &#9873; Data Tag
This `<data>` tag is used to specifies content which readable by human as well as machine.

*The content can holds `value=""` attribute that readable and usable by machine.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<data>` tag created as, 
```xml
<data value="{{machine-readable-value}}">{{Content}}</data>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **value** - It specifies machine readable value with respect to the content.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<data>` tag
```xml
<h3>User Name : <data value="skfj89s7fsh">Kumar</data></h3>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/data-tag.html)

---
[&#8682; To Top](#-data-tag)

[&#10094; Previous Topic](./colgroup-tag.md) &emsp; [Next Topic &#10095;](./datalist-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
