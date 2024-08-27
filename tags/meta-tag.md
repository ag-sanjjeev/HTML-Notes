## &#9873; Meta Tag
This `<meta>` tag is used to specifies the machine readable information about the HTML document.

*This can be represented inside the [`head`](./head-tag.md) tag. Which holds the metadata that means information related to HTML document such as character set of the page, page viewport setting, page descriptions, keywords and author of the document and etc.,*

*This is used by the web browsers that how to display this current HTML document. Search Engines uses this meta information to give desired the search result.*

*Basically, It is not visible part of the web page.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<meta>` tag created as, 
```xml
<meta name="{{name-of-the-information}}" content="{{information}}">
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **name** - It specifies name/type of the information.
2. **content** - It specifies information related to given name/type.
3. **charset** - It specifies character encoding of the current HTML document.
4. **http-equiv** - It specifies an HTTP header information of content attribute.

### &#10022; Event Attributes:
This tag does not support any of the event attributes.

### &#10022; Examples:
> Example for `<meta>` tag to setting character set
```xml
<meta charset="utf-8">
```

> Example for `<meta>` tag to setting viewport
```xml
<meta name="viewport" content="width=device-width,initial-scale=1.0">
```

> Example for `<meta>` tag to defining description of the page
```xml
<meta name="description" content="This is a web page description">
```

> Example for `<meta>` tag to defining keywords for search engine
```xml
<meta name="keywords" content="Front-End Development, HTML, CSS, JavaScript" >
```

> Example for `<meta>` tag to define author of the page
```xml
<meta name="author" content="kumar">
```

> Example for `<meta>` tag to refresh page at every 1000 seconds
```xml
<meta http-equiv="refresh" content="1000">
```

### &#10022; Code Reference:

See this [`Code Reference`](../code/meta-tag.html)

---
[&#8682; To Top](#-meta-tag)

[&#10094; Previous Topic](./mark-tag.md) &emsp; [Next Topic &#10095;](./meter-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
