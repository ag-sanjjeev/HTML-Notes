## &#9873; Form Tag
This `<form>` tag is used to group the interactive control elements and information to be submitted as application form in HTML document.

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<form>` tag created as, 
```xml
<form action="{{URL/Location}}" method="{{form-submission-method}}">
	...
</form>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **action** - It specifies URL/Location where the form to be submitted.
2. **method** - It specifies HTTP method when sending a form data.
3. **enctype** - It specifies encoded type to encode form data when submitting.
4. **target** - It determines the form response where to be displayed.
5. **name** - It specifies name of the form.
6. **autocomplete** - It specifies the form element to be autocomplete when user input or not.
7. **novalidate** - It specifies that the form is not to be validated before submitted.
8. **rel** - It specifies the relationship between the current document and linked resource.
9. **accept-charset** - It specifies character encoding for the form to be submitted.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<form>` tag
```xml
<form id="loginForm">
	<label for="username">User Name</label>
	<input type="text" name="username" id="username" />

	<label for="password">Password</label>
	<input type="password" name="password" id="password" />

	<button type="submit">Login</button>
</form>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/form-tag.html)

---
[&#8682; To Top](#-form-tag)

[&#10094; Previous Topic](./footer-tag.md) &emsp; [Next Topic &#10095;](./h1-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
