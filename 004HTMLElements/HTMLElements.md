# HTML Elements

- start tag + content + end tag

## HTML Elements

- HTML Element = everything from the start tag to the end tag
```html
<tagname>Content</tagname>
```

Examples:
```html
<h1>Heading</h1>
<p>Paragraph</p>
<br>Empty Element
```

## Nested HTML Elements

```html
<!DOCTYPE html>
    <html>
        <body>

            <h1>My First Heading</h1>
            <p>My first paragraph.</p>

        </body>
    </html>
```

## Never Skip the End Tag

- some elements display correctly without the end tag, but expect unexpected results!
```html
<html>
<body>

<p>This is a paragraph
<p>This is a paragraph

</body>
</html>
```

## Empty HTML Elements

- `<br>`: line break
```html
<p>This is a <br> paragraph with a line break.</p>
```

## HTML is Not Case Sensitive

- `<P>` = `<p>`
- W3C recommends lowercase in HTML
- W3C demands lowercase for stricter document types like XHTML

## HTML Tag Reference

https://www.w3schools.com/tags/default.asp