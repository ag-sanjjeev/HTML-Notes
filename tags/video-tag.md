## &#9873; Video Tag
This `<video>` tag is used to embed video content in the HTML document. 

*This video contents can be embedded using `src=""` attribute or using [`<source>`](./source-tag.md) tag. [`<source>`](./source-tag.md) tag may contain one or more video contents. Browser will choose one of the first source supports to play.*

*It can supports audio file to play. For better controls over audio file, use [`<audio>`](./audio-tag.md) tag.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<video>` tag created as, 
```xml
<video controls>
	<source src="{{video-file-url}}" type="{{video-type}}">	
</video>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **src** - It specifies URL/Location of the video file to embed.
2. **controls** - It displays the video controls to do play, pause and volume control.
3. **autoplay** - It specifies that the video will play automatically once the file being ready.
4. **loop** - It specifies that playback will start over again once finished or completed.
5. **muted** - It specifies that playback will be muted.
6. **preload** - It specifies that when to load the video.	
7. **poster** - It specifies the image URL/Location to be shown as thumbnail until video loading or not yet played.	

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<video>` tag
```xml
<video controls>
	<source src="videos/company-documentary.webm" type="video/webm">
	<source src="videos/company-documentary.mp4" type="video/mp4">
	<source src="videos/company-documentary.avi" type="video/x-msvideo">	
</video>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/video-tag.html)

---
[&#8682; To Top](#-video-tag)

[&#10094; Previous Topic](./var-tag.md) &emsp; [Next Topic &#10095;](./wbr-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
