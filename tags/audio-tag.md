## &#9873; Audio Tag
This `<audio>` tag is used to embed sound content in the HTML document. 

*This sound contents can be embedded using `src=""` attribute or using [`<source>`](./source-tag.md) tag. [`<source>`](./source-tag.md) tag may contain one or more audio contents. Browser will choose one of the first source supports to play.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<audio>` tag created as, 
```xml
<audio controls>
	<source src="{{audio-file-url}}" type="{{audio-type}}">	
</audio>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **src** - It specifies URL/Location of the audio file to embed.
2. **controls** - It displays the audio controls to do play, pause and volume control.
3. **autoplay** - It specifies that the audio will play automatically once the file being ready.
4. **loop** - It specifies that playback will start over again once finished or completed.
5. **muted** - It specifies that playback will be muted.
6. **preload** - It specifies that when to load the audio.	

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<audio>` tag
```xml
<audio controls>
	<source src="voice.mp3" type="audio/mpeg">
	<source src="background-music.ogg" type="audio/ogg">	
</audio>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/audio-tag.html)

---
[&#8682; To Top](#-audio-tag)

[&#10094; Previous Topic](./aside-tag.md) &emsp; [Next Topic &#10095;](./b-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
