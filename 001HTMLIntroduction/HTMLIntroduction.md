# HTML

- the standard markup language for creating Web pages

## What is HTML?

- Hyper Text Markup Language
- standard markup language for creating Web pages
- describes structure of a Web page
- consists of series of elements
- elements tell browser how to display the content
- elements label pieces of content: heading, paragraph, link, etc.

Sample HTML document:
```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
``````

- `<!DOCTYPE html>` declaration: defines documents as HTML5 document
- `<html>` element: root element of an html page
- `<head>` element: contains meta info about the html page
- `<title>` element: specifies title for HTML page, shown in browser's title var or page tab
- `<body>` element: defines body, container for all visible content (headings, paragraphs, images, hyperlinks, tables, lists, etc.)
- `<h1>` element: defines a large heading
- `<p>` element: defines a paragraph

## What is an HTML Element?

start tag + content + end tag
```html
<tagname> content goes here... </tagname>
```

Examples:
```html
<h1>My First Heading</h1>
<p>My First Paragraph</p>
<br>My First Empty Element
```
- Some elements like `<br>` have no content and are called *empty elements*, they have no end tag!

## Web Browsers

- purpose of web browsers is to read and display HTML documents correctly
- browser uses tags to determine how to display content correctly

## HTML Page Structure
```html
<html>
    <head>
        <title>Page title</title>
    </head>
    <body>
        <h1>This is a heading</h1>
        <p>This is a paragraph</p>
        <p>This is another paragraph</p>
    </body>
</html>
```
- content in the `<body>` will be displayed in the browser
- content in the `<title>` will be shown in browser title bar or page tab

## HTML History
|Year|Version|
|---|---|
|1989| Tim Berners-Lee invented www|
|1991| Tim Berners-Lee invented HTML|
|1993| Dave Raggett drafted HTML+|
|1995|	HTML Working Group defined HTML 2.0|
|1997|	W3C Recommendation: HTML 3.2|
|1999|	W3C Recommendation: HTML 4.01|
|2000|	W3C Recommendation: XHTML 1.0|
|2008|	WHATWG HTML5 First Public Draft|
|2012|	WHATWG HTML5 Living Standard|
|2014|	W3C Recommendation: HTML5|
|2016|	W3C Candidate Recommendation: HTML 5.1|
|2017|	W3C Recommendation: HTML5.1 2nd Edition|
|2017|	W3C Recommendation: HTML5.2|