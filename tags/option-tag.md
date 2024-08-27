## &#9873; Option Tag
This `<option>` tag is used to specify the option or list item in the [`<select>`](./select-tag.md) tag or [`<datalist>`](./datalist-tag.md) tag.

*This can be created without `value` attribute. But `value` attribute is essential when submitting form.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<option>` tag created as, 
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
1. **value** - It specifies the value of the option.
2. **selected** - It specifies that option to be selected by default.
3. **disabled** - It specifies that option to be disabled to choose.
4. **label** - It specifies that shorter label for option.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<option>` tag
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

See this [`Code Reference`](../code/option-tag.html)

---
[&#8682; To Top](#-option-tag)

[&#10094; Previous Topic](./optgroup-tag.md) &emsp; [Next Topic &#10095;](./output-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
