# HTML Table Borders

HTML tables can have borders of different styles and shapes.

## How To Add a Border

When you add a border to a table, you also add borders around each table cell.

To add a border, use the CSS `border` property on `table`, `th` and `td` elements:

```css
table, th, td {
  border: 1px solid black;
}
```

## Collapsed Table Borders

To avoid having double borders like in the example above, set the CSS `border-collapse` property to `collapse`.

This will make the borders collapse into a single border:

```css
table, th, td {
  boder: 1px solid black;
  border-collapse: collapse;
}
```

## Style Table Borders

If you set a background color of each cell, and give the border a white color (the same as the document background), you get the impression of an invisible border:

```css
table, th, td {
  border: 1px solid white;
  border-collapse: collapse;
}
th, td {
  backgound: #96D4D4;
}
```

## Round Table Borders

With the `border-radius` property, the borders get rounded corners:

```css
table, th, td {
  boder: 1px solid black;
  border-radius: 10px
}
```