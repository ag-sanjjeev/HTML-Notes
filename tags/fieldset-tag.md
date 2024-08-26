## &#9873; Fieldset Tag
This `<fieldset>` tag is used to group several form elements.

*This group can be labeled or named using [`<legend>`](./legend-tag.md) tag.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<fieldset>` tag created as, 
```xml
<fieldset>
	....
	form elements and labels
	...
</fieldset>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **disabled** - It specifies that the group of elements to be disabled.
2. **form** - It specifies that group belongs to which form id. 
3. **name** - It specifies the name of the fieldset group. 

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<fieldset>` tag
```xml
<form id="loginForm">
	<fieldset>
		<legend>Login Form</legend>
		<label for="username">User Name</label>
		<input type="text" name="username" id="username" />

		<label for="password">Password</label>
		<input type="password" name="password" id="password" />

		<button type="submit">Login</button>
	</fieldset>
</form>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/fieldset-tag.html)

---
[&#8682; To Top](#-fieldset-tag)

[&#10094; Previous Topic](./embed-tag.md) &emsp; [Next Topic &#10095;](./figcaption-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
