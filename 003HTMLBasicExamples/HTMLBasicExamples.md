# HTML Basic Examples

## HTML Documents
- all HTML documents start with document type declaration `<!DOCTYPE html>`
- HTML document itself begins and ends with `<html>` and `</html>`
- the visible part of the document is between `<body>` and `</body>`

## The <!DOCTYPE> Declaration

- tells the browser the document type so the browser can display the web page correctly
- only appears once at the top of the page
- is not case sensitive
- for HTML5 looks like:
```html
<!DOCTYPE html>
```

## HTML Headings
- from `<h1>` to `<h6>`, from most important to least important
```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
```

## HTML Paragraphs
- use `<p>` tag
```html
<p>First paragraph</p>
<p>Second paragraph</p>
```

## HTML Links
- defined with the `<a>` tag
```html
<a href="https://www.w3schools.com">This is a link</a>
```
- `href` attribute specifies link destination

## HTML Images
- define with `<img>` tag
- attributes: 
    - `src`: source file
    - `alt`: alternative text
    - `width`
    - `height`
```html
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```

## How to View HTML Source
- right click on page > View Page Source
- right click element > Inspect: see HTML + CSS, as well as edit it in the Elements/Styles panel