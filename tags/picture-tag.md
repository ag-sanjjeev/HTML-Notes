## &#9873; Picture Tag
This `<picture>` tag is used to display images for different viewport setting..

*This will match `media` attribute in the [`<source>`](./source-tag.md) elements and display the respective image. And if none of the `media` attributes matches then the last [`<img>`](./img-tag.md) element to be displayed.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<picture>` tag created as, 
```xml
<picture>
	<source src="{{Image URL/Location}}" type="{{media-type}}" media="{{media-setting}}">
	<source src="{{Image URL/Location}}" type="{{media-type}}" media="{{media-setting}}">
	<source src="{{Image URL/Location}}" type="{{media-type}}" media="{{media-setting}}">
	<img src="{{final-image}}" alt="{{alternative-text}}">
</picture>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<picture>` tag
```xml
<picture>
	<source src="images/pink-flower-mini.jpeg" type="image/jpeg" media="(min-width:300px)">
	<source src="images/pink-flower-medium.jpeg" type="image/jpeg" media="(min-width: 768px)">	
	<img src="images/pink-flower-full.jpeg" alt="pink-flower">
</picture>
```

### &#10022; Code Reference:

See this [`Code Reference`](../code/picture-tag.html)

---
[&#8682; To Top](#-picture-tag)

[&#10094; Previous Topic](./param-tag.md) &emsp; [Next Topic &#10095;](./pre-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
