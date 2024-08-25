## &#9873; Colgroup Tag
This `<colgroup>` tag is used to specifies group of columns within a table for formatting.

*This must be a child element of the table, after table caption `<caption>` tag and any before the `<thead>`, `<tbody>` and `<tfoot>` tags.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<colgroup>` tag created as, 
```xml
<colgroup span="{{columns-span-value-if-required}}" style="{{style-to-apply-this-columns-span}}">
	<col span="{{column-span-value-if-required}}" style="{{style-to-apply-this-column-span}}">
	<col style="{{style-to-apply-this-column-span}}">
</colgroup>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **span** - It specifies that number of columns as a group to span.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<colgroup>` tag
```xml
<table>
	<caption>Library Report</caption>
	<colgroup span="2" style="background-color: #FF2B3C;">
		<col style="background-color: initial;">
		<col style="background-color: initial;">				
		<col style="background-color: #12ABFF;">
	</colgroup>
	<thead>
		<th>S.NO</th>
		<th>Book Name</th>
		<th>Total Readers</th>		
	</thead>
	<tbody>
		<tr>
			<td>1.</td>
			<td>Learn HTML for the beginners</td>
			<td>1100</td>			
		</tr>
		<tr>
			<td>2.</td>
			<td>Practical Way to Front-End Web Development</td>			
			<td>650</td>
		</tr>
	</tbody>
</table>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/colgroup-tag.html)

---
[&#8682; To Top](#-colgroup-tag)

[&#10094; Previous Topic](./col-tag.md) &emsp; [Next Topic &#10095;](./data-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
