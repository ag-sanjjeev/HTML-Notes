## &#9873; Table Header Cell Tag
This `<th>` tag is used to specifies the column heading of the tabular information in the HTML document.

*This always child element of [`tabular header group`](./thead-tag.md).*

### &#9780; Overview:
1. [Syntax](#-syntax),
2. [Attributes and Properties](#-attributes-and-properties),
3. [Event Attributes](#-event-attributes),
4. [Examples](#-examples),
5. [Code Reference](#-code-reference)

### &#10022; Syntax:
Simple `<th>` tag created as, 
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
</table>
```

### &#10022; Attributes and Properties:
This can support most of the standard [attributes and properties](../docs/attributes-and-properties.md).
And also support some other below:
1. **abbr** - It specifies the abbreviated version of header cell.
2. **scope** - It specifies the header cell is a header for column or row or group of columns or group of rows.
3. **headers** - It specifies that one or more header cells is a cell is related to it.
4. **rowspan** - It specifies the number of rows to be span for a cell.
5. **colspan** - It specifies the number of cells to be span for a cell.

### &#10022; Event Attributes:
This can support most of the standard [events](../docs/events.md).

### &#10022; Examples:
> Example for `<th>` tag
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
</table>
```

### &#10022; Code Reference:
See this [`Code Reference`](../code/th-tag.html)

---
[&#8682; To Top](#-table-header-cell-tag)

[&#10094; Previous Topic](./tfoot-tag.md) &emsp; [Next Topic &#10095;](./thead-tag.md)

[&#8962; Goto Home Page](../README.md) &emsp; [&#9776; Goto All Tags](../all-tags.md)
