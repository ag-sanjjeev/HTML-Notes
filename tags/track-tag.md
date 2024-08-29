## &#9873; Track Tag
This `<track>` tag is used to specifies the subtitle for [`<audio>`](./audio-tag.md) and [`<video>`](./video-tag.md) tags.

*This subtitle tracks will only supports in WebVTT format (.vtt) files.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<track>` tag created as, 
```xml
<track kind="{{kind-of-the-track}}" src="{{URL/Location-of-the-track}}">
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **kind** - It specifies the kind of text track such as captions, chapters, descriptions, metadata and subtitle.
2. **src** - It specifies URL/Location for subtitle track.
3. **srclang** - It specifies the language of the track text data when `kind="subtitle"`.
4. **label** - It specifies the title of the text track.
5. **default** - It specifies the default track for the user. Even though browser prefers appropriate track.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<track>` tag
```xml
<video controls>
	<source src="videos/company-documentary.webm" type="video/webm">
  <source src="videos/company-documentary.mp4" type="video/mp4">
  <source src="videos/company-documentary.avi" type="video/x-msvideo">
  <track kind="subtitle" src="videos/company-documentary-subtitles_en.vtt" srclang="en" label="English">
  <track kind="subtitle" src="videos/company-documentary-subtitles_ta.vtt" srclang="ta" label="Tamil">
</video>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/track-tag.html)

---
[&#8682; To Top](#-track-tag)

[&#10094; Previous Topic](./tr-tag.md) &emsp; [Next Topic &#10095;](./u-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
