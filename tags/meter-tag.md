## &#9873; Meter Tag
This `<meter>` tag is used to specifies the scalar measurement or linear meter gauge.

*This will defines a scalar measurement within specified range or fractional value. This `<meter>` tag should not be used as progress bar. Use [`<progress>`](./progress-tag.md) tag for progress bars.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<meter>` tag created as, 
```xml
<meter value="{{present-value}}" min="{{minimum-value}}" max="{{maximum-value}}"></meter>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **min** - It specifies minimum value of the meter range. Default is 0.
2. **max** - It specifies maximum value of the meter range.
3. **low** - It specifies the range that considered to be a low value.
3. **high** - It specifies the range that considered to be a high value.
3. **value** - It specifies the present value of the meter or gauge.
3. **optimum** - It specifies the optimum value for the meter or gauge.
3. **form** - It specifies the meter belongs to the form id.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<meter>` tag
```xml
<meter value="10" min="0" max="1000"></meter>
```

### &#10022; Code Reference:

See this [`Code Reference`](../code/meter-tag.html)

---
[&#8682; To Top](#-meter-tag)

[&#10094; Previous Topic](./meta-tag.md) &emsp; [Next Topic &#10095;](./nav-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
