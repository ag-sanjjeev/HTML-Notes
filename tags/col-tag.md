## &#9873; Col Tag
This `<col>` tag is used to specifies HTML table column properties for each column inside a `<colgroup>` tag.

*This `<col>` tag is only valid when inside of the `<colgroup>` tag in the HTML table. This will helpful to apply styles for each column in the table, instead of apply in each cells in a table.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:

Simple `<col>` tag created as, 
```xml
<colgroup>
	<col span="{{column-span-value-if-required}}" style="{{style-to-apply-this-column-span}}">
	<col style="{{style-to-apply-this-column-span}}">
</colgroup>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **span** - It specifies that number of columns to take into action.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<col>` tag
```xml
<table>
	<caption>Library Report</caption>
	<colgroup>
		<col span="2" style="background-color: #12ABFF;">
		<col style="background-color: #FF2B3C;">
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
See this [`Code Reference`](../code/col-tag.html)

---
[&#8682; To Top](#-col-tag)

[&#10094; Previous Topic](./code-tag.md) &emsp; [Next Topic &#10095;](./colgroup-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
