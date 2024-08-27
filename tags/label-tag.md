## &#9873; Label Tag
This `<label>` tag is used to specify the label for input elements.

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<label>` tag created as, 
```xml
<label for="{{element-id}}">{{label name}}</label>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **for** - It specifies the label element to be bounded with input element.
2. **form** - It specifies the label belongs to the form id. 

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<label>` tag
```xml
<label for="username">User Name</label>
<input type="text" name="username" id="username" placeholder="Enter your user name" />
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/label-tag.html)

---
[&#8682; To Top](#-label-tag)

[&#10094; Previous Topic](./kbd-tag.md) &emsp; [Next Topic &#10095;](./legend-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
