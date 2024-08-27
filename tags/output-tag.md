## &#9873; Output Tag
This `<output>` tag is used to specify the result or output from the site or application in the HTML document.

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<output>` tag created as, 
```xml
<output name="{{name-of-the-output}}" for="{{relationship of the elements}}"></output>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **name** - It specifies the name of the output.
2. **for** - It specifies the relationship between output element and elements used.
3. **form** - It specifies that output element belongs to form id.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<output>` tag
```xml
<form oninput="sum.value=Number(a.value) + Number(b.value)">
	<input type="number" name="a" value="0" min="0" /> + 
	<input type="number" name="b" value="0" min="0" /> = 
	<output name="sum" for="a b"></output>
</form>
```

### &#10022; Code Reference:

See this [`Code Reference`](../code/output-tag.html)

---
[&#8682; To Top](#-output-tag)

[&#10094; Previous Topic](./option-tag.md) &emsp; [Next Topic &#10095;](./p-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
