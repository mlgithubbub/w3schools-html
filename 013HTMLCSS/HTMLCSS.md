# HTML Styles - CSS

- CSS stands for Cascading Style Sheets
- CSS saves a lot of work because can control layout of multiple web pages at once

## What is CSS?

- CSS is used to format the layout of a webpage
- you can control the color, font, text size, spacing, position, background images/colors, different displays for different devices, etc.
- *cascading* means that a style applied to a parent element will also apply to all children elements of that parent

## Using CSS

- CSS can be added to an HTML document in 3 ways:
    1. Inline: using `style` attribute inside HTML elements
    2. Internal: using `<style>` element in the `<head>` section
    3. External: using `<link>` element to link to an external CSS file
- External CSS files are most common

## Inline CSS

- applies a style to a single HTML element
- uses the `style` attribute of an HTML element

```html
<h1 style="color:blue;">A Blue Heading</h1>

<p style="color:red;">A red paragraph.</p>
```

## Internal CSS

- defines style for a single HTML page
- defined in the `<head>` section of an HTML page within a `<style>` element


```html
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

## External CSS

- defines the style for many HTML pages
- add a link to the external style sheet in the `<head>` section of each HTML page

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

- the external style sheet can be written in any text editor
- the file should not contain any HTML code
- the file should be saved with a .css extension

styles.css :
```css
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
```

## CSS Colors, Fonts and Sizes

- `color` property: defines text color
- `font-family` property: defines font
- `font-size` property: defines font size

```html
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;
}
p {
  color: red;
  font-family: courier;
  font-size: 160%;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

## CSS Border

- `border` property: defines border around HTML element

```html
p {
  border: 2px solid powderblue;
}
```

## CSS Padding

- `padding` property defines padding (space) between text and border

```css
p {
  border: 2px solid powderblue;
  padding: 30px;
}
```

## CSS Margin

- `margin` property defines margin (space) outside the border

```css
p {
  border: 2px solid powderblue;
  margin: 50px;
}
```

## Link to External CSS

- external style sheets can be referenced with a full URL or with a path relative to the current web page

Full URL:
```html
<link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">
```

Linking to a style sheet located in the HTML folder on the current web site:
```html
<link rel="stylesheet" href="/html/styles.css">
```

Linking to a style sheet located in the same folder as the current page:
```html
<link rel="stylesheet" href="styles.css">
```
