## &#9873; Select Tag
This `<select>` tag is used to add drop-down list or multiple choice option menu to select one or more by the user.

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<select>` tag created as, 
```xml
<select>
	<option value="{{option-value}}">{{option 1}}</option>
	<option value="{{option-value}}">{{option 2}}</option>
	<option value="{{option-value}}">{{option 3}}</option>	
</select>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **name** - It specifies the name for the select element. 
2. **disabled** - It prevents the select options being selectable or choose.
3. **form** - It specifies that select element belongs to which form id.
4. **multiple** - It specifies that more than one option to select.
5. **required** - It specifies that the atleast one option to be selected before form submission.
6. **size** - It specifies that number of visible options in the select element.
7. **autofocus** - It specifies that select element to be focused automatically when page loads.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<select>` tag 
```xml
<select name="fruits">
	<option value="orange">Orange</option>
	<option value="pineapple">Pineapple</option>
	<option value="strawberry">Strawberry</option>
</select>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/select-tag.html)

---
[&#8682; To Top](#-select-tag)

[&#10094; Previous Topic](./section-tag.md) &emsp; [Next Topic &#10095;](./small-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
