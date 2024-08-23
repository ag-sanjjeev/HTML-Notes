## &#9873; Anchor Tag
This `<a>` tag defines hyperlink in the HTML documents. Which is used to link another web page or section.

*The most important attribute used in **a** tag is **href**. That holds destination **URL/Location** to link.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<a>` tag created as, 
```xml
<a href="{{url/location}}">Link Text</a>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **href** - It specifies URL/Location to link.
2. **hreflang** - It specifies the language of the linked page/section.
3. **target** - It decides where to open the link.
4. **media** - It specifies what type of media/device that page/section optimized.
5. **download** - It will download the target file when user clicks.
6. **type** - It specifies which media type of the document or page linked. 
7. **rel** - It specifies relationship between the current document and the linked document.
8. **ping** - It holds list of space separated URLs, which sent post requests by the browser in background. (Typically for tracking purposes).
9. **referrerpolicy** - It sent referrer information with the link.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for href attribute
```xml
<a href="index.html">Home Page</a>
```
> Example for hreflang attribute 
```xml
<a href="index.html" hreflang="en">Home Page</a>
```
> Example for target attribute
```xml
<a href="report.html" target="_blank">Open Report</a>
```
> Example for media attribute
```xml
<a href="final-receipt.php" media="print and (resolution:300dpi)">Print Receipt</a>
```
> Example for download attribute
```xml
<a href="/images/image.jpg" download>Download Image</a>
```
> Example for type attribute
```xml
<a href="index.html" type="text/html">Home Page</a>
```
> Example for rel attribute
```xml
<a href="license.html" rel="license">See License</a>
```
> Example for ping attribute
```xml
<a href="index.html" ping="tracking.php">Home Page</a>
```
> Example for referrerpolicy attribute
```xml
<a href="index.html" referrerpolicy="same-origin">Home Page</a>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/a-tag.html)

---
[&#8682; To Top](#-anchor-tag)

[&#10094; Previous Topic](./doctype.md) &emsp; [Next Topic &#10095;](./abbr-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
