## &#9873; Table Foot Tag
This `<tfoot>` tag is used to specifies the group of cells to be represented as a footer of the tabular information in the HTML document.

*This is used for summary of the tabular information such as sum of the values represented in the cells.*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<tfoot>` tag created as, 
```xml
<table>
	...
	<thead>
		<th>...</th>
		<th>...</th>
	</thead>
	<tbody>
		<tr>
			<td>...</td>
			<td>...</td>
		</tr>
		<tr>...</tr>
	</tbody>
	<tfoot>
		<tr>...</tr>
		<tr>...</tr>
	</tfoot>
</table>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<tfoot>` tag
```xml
<table>
	<caption>Staff Report</caption>
	<thead>
		<th>S.No</th>
		<th>Positions</th>
		<th>No. of Employees</th>
	</thead>
	<tbody>
		<tr>
			<td>1</td>
			<td>Managers</td>
			<td>5</td>
		</tr>
		<tr>
			<td>2</td>
			<td>Team Leaders</td>
			<td>20</td>
		</tr>
		<tr>
			<td>3</td>
			<td>Senior Developers</td>
			<td>25</td>
		</tr>
		<tr>
			<td>4</td>
			<td>Junior Developers</td>
			<td>100</td>
		</tr>
		<tr>
			<td>5</td>
			<td>Office Staff</td>
			<td>20</td>
		</tr>
	</tbody>
	<tfoot>
		<tr>
			<td align="center" colspan="2">Total Employees</td>
			<td>170</td>
		</tr>
	</tfoot>
</table>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/tfoot-tag.html)

---
[&#8682; To Top](#-table-foot-tag)

[&#10094; Previous Topic](./textarea-tag.md) &emsp; [Next Topic &#10095;](./th-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
