## &#9873; Inline Frame Tag
This `<iframe>` tag is used to add external web page or another HTML content in the current HTML document.

*This will give nested browsing content to the current HTML document.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<iframe>` tag created as, 
```xml
<iframe src="{{URL/Location}}" title="{{Title for the inline frame}}"></iframe>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **name** - It specifies the name of the iframe.
2. **src** - It specifies URL/Location for the external content.
3. **srcdoc** - It shows the specific HTML Content of the page.
4. **loading** - It allows to load immediately or defer loading until some conditions are met using the value `eager` or `lazy`.
5. **referrerpolicy** - It specifies referrer information to send when fetching external content.
6. **sandbox** - It sets extra layer of restriction for the content of an iframe.
7. **allow** - It specifies the feature policies for the iframe.
8. **allowfullscreen** - It specifies to allow full screen mode or not.
9. **allowpaymentrequest** - It allows cross-origin iframe content to request for the Payment Request API. 

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<iframe>` tag
```xml
<iframe src="https://www.exampledomainnamesite.com/post/article-1" title="Reference Source"></iframe>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/iframe-tag.html)

---
[&#8682; To Top](#-inline-frame-tag)

[&#10094; Previous Topic](./i-tag.md) &emsp; [Next Topic &#10095;](./img-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
