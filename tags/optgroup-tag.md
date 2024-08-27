## &#9873; Option Group Tag
This `<optgroup>` tag is used to create a grouping of options within a [`<select>`](./select-tag.md) tag.

*This can helpful to group the long list of options into categorized options or group of options.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<optgroup>` tag created as, 
```xml
<select>
	<optgroup label="{{group-name}}">
		<option value="{{option-value}}">{{option 1}}</option>
		<option value="{{option-value}}">{{option 2}}</option>
		<option value="{{option-value}}">{{option 3}}</option>
	</optgroup>
	<optgroup label="{{group-name}}">
		<option value="{{option-value}}">{{option 4}}</option>
		<option value="{{option-value}}">{{option 5}}</option>
		<option value="{{option-value}}">{{option 6}}</option>
	</optgroup>
</select>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **label** - It specifies the label for an option group.
2. **disabled** - It specifies that option group to be disabled.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<optgroup>` tag
```xml
<select>
	<optgroup label="Fruits">
		<option value="orange">Orange</option>
		<option value="pineapple">Pineapple</option>
		<option value="strawberry">Strawberry</option>
	</optgroup>
	<optgroup label="Vegetables">
		<option value="carrot">Carrot</option>
		<option value="drumstick">Drumstick</option>
		<option value="potato">Potato</option>
	</optgroup>
</select>
```

### &#10022; Code Reference:

See this [`Code Reference`](../code/optgroup-tag.html)

---
[&#8682; To Top](#-option-group-tag)

[&#10094; Previous Topic](./ol-tag.md) &emsp; [Next Topic &#10095;](./option-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
