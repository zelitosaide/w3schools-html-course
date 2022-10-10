# HTML Table Colspan & Rowspan

HTML tables can have cells that span over multiple rows and/or columns.

## HTML Table - Colspan

To make a cell span over multiple columns, use the `colspan` attribute:

```html
<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </td>
</table>
```

> **Note:** The value of the `colspan` attribute represents the number of columns to span.

## HTML Table - Rowspan

To make a cell span over multiple rows, use the rowspan attribute:

```html
<table>
  <tr>
    <th>Name</th>
    <td>Jill</td>
  </tr>
  <tr>
    <th rowspan="2">Phone</th>
    <td>555-1234</td>
  </tr>
  <tr>
    <td>555-8745</td>
  </tr>
</table>
```

> **Note:** The value of the `rowspan` attribute represents the number of rows to span.