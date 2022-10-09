# HTML Table Headers

HTML tables can have headers for each column or row, or for many columns/rows.

## HTML Table Headers

Table headers are defined with `th` elements. Each `th` element represents a table cell.

```html
<table>
  <tr>
    <th>First Name</th>
    <th>Last Name</th>
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
  </tr>
</table>
```

## Vertical Table Headers

To use the first column as table headers, define the first cell in each row as a `<th>` element:

```html
<table>
  <tr>
    <th>First Name</th>
    <td>Jill</td>
    <td>Eve</td>
  </tr>
  <tr>
    <th>Last Name</th>
    <td>Smith</td>
    <td>Jackson</td>
  </tr>
  <tr>
    <th>Age</th>
    <td>50</td>
    <td>94</td>
  </tr>
</table>
```

## Align Table Headers

By default, table headers are bold centered.

To left-align the table headers, use the CSS `text-align` property:

```css
th {
  text-align: left;
}
```

## Header for Multiple Columns

You can have a header that spans over two or more columns.

To do this, use the `colspan` attribute on the `<th>` element:

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

> You will learn more about colspan and rowspan in the [Table colspan & rowspan](https://www.w3schools.com/html/html_table_colspan_rowspan.asp) chapter.

## Table Caption

You can add a caption that serves as a heading for the entire table.

To add a caption to a table, use the `<caption>` tag:

```html
<table style="width:100%">
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$50</td>
  </tr>
</table>
```


> **Note:** the `<caption>` tag should be inserted immediately after the `<table>` tag.