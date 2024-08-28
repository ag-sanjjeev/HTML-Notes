## &#9873; Script Tag
This `<script>` tag is used to embed executable code and data.

*Usually, This `<script>` element can used to refer JavaScript Code and JSON data.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<script>` tag created as, 
```xml
<script type="text/javascript">
	...
</script>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **type** - It specifies the media type of the script.
2. **src** - It specifies the URL/Location of the script.
3. **referrerpolicy** - It sent referrer information when fetching script.
4. **crossorigin** - It sets cross-origin access to the script.
5. **defer** - It specifies that the script will be downloaded in parallel. And it executes after the page loads completely. It is best practice for external scripts.
6. **integrity** - It allows the browser to check and ensure that external script is never loaded and not to be manipulated from origin. 
7. **async** - It specifies that the script will be downloaded in parallel and it starts to execute once the script is completely available before the page is completely parsed and rendered. It is best practice for external script.
8. **nomodule** - It specifies that the script will not be executed in browsers.

### &#10022; Event Attributes:
This tag does not support any of the event attributes.

### &#10022; Examples:
> Example for `<script>` tag loaded within an HTML document
```xml
<script type="text/javascript">
	let message = 'Welcome to this site';
	alert(message);
</script>
```

> Example for `<script>` tag loaded from external
```xml
<script type="text/javascript" src="https://www.exampledomainnamesite.com/plugins/analytics.min.js"></script>
```

### &#10022; Code Reference:

See this [`Code Reference`](../code/script-tag.html)

---
[&#8682; To Top](#-script-tag)

[&#10094; Previous Topic](./samp-tag.md) &emsp; [Next Topic &#10095;](./section-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
