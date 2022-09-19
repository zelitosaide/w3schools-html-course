# HTML Basic Examples

In this chapter we will show some basic HTML examples.

Don't worry if we use tags you have not learned about yet.

## HTML Documents

All HTML documents must start with a document type declaration: `<!DOCTYPE html>`.

The HTML document itself begins with `<html>` and ends with `</html>`.

The visible part of the HTML document is between `<body>` and `</body>`. 

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>My First Heading</h1>
    <p>My First paragraph.</p>
  </body>
</html>
```

## The <!DOCTYPE> Declaration

The `<!DOCTYPE>` declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The `<!DOCTYPE>` declaration is not case sensitive.

The `<!DOCTYPE>` declaration for HTML5 is:

```html
<!DOCTYPE html>
```

## HTML Headings

HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading: 

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>This is heading 1</h1>
    <h2>This is heading 2</h2>
    <h3>This is heading 3</h3>
    <h4>This is heading 4</h4>
    <h5>This is heading 5</h5>
    <h6>This is heading 6</h6>
  </body>
</html>
```

## HTML Paragraphs

HTML paragraphs are defined with the `<p>` tag:

```html
<!DOCTYPE html>
<html>
  <body>
    <p>This is a paragraph.</p>
    <p>This is another paragraph.</p>
  </body>
</html>
```

## HTML Links

HTML links are defined with the `<a>` tag:

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>HTML Links</h1>
    <p>
      HTML links are defined with the "a" tag:
    </p>

    <a href="https://www.w3schools.com">
      This is a link
    </a>
  </body>
</html>
```