# HTML Attributes

- provide additional info about HTML elements

## HTML Attributes

- all HTML elements can have attributes
- attributes provide additional info about elements
- attributes are always specified in the start tag
- attributes usually come in name-value pairs: `name="value"`

### The href Attribute

- `<a>` tag defines a hyperlink
- `href` attribute specifies URL of the page that the link goes to

```html
<a href="https://www.w3schools.com">Visit W3Schools</a>
```

### The src Attribute

- `<img>` tag is used to embed image in an HTML page
- `src` attribute specifies path to image to be displayed

```html
<img src="img_girl.jpg">
```
- **absolute URL**: links to image hosted on another website
    - ex: src="https://www.w3schools.com/images/img_girl.jpg"
    - may be under copyright
    - can suddenly be removed or changed
- **relative URL**: links to image hosted within website
    - does not include the domain name
    - if without a slash, relative to the current page: src="img_girl.jpg"
    - if with a slash, relative to the domain: src="/images/img_girl.jpg"
    - best to use relative URLs

### Width and Height Attributes

- `<img>` tag should also contain `width` and `height` attributes

```html
<img src="img_girl.jpg" width="500" height="600">
```

### The alt Attribute

- `alt` specifies and alternate text for an image, if the image cannot be displayed for some reason

```html
<img src="img_girl.jpg" alt="Girl with a jacket">
```

### The style Attribute

- `style` adds color, font, size, etc. to an element

```html
<p style="color:red;">This is a red paragraph.</p>
```
### The lang Attribute

- always include the `lang` attribute inside the `<html>` tag to declare the language of a Web page (assists search engines and browsers)

```html
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```

- you can also add country codes to the language code in the `lang` attribute:

```html
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
```

- all language codes: https://www.w3schools.com/tags/ref_language_codes.asp

### The title Attribute

- `title` defines some extra info about an element
- the value will be displayed as a tooltip when you mouse over the element

```html
<p title="I'm a tooltip">This is a paragraph.</p>
```

### Suggestions:

- Always use lowercase attributes
- Always quote attributes, because without quotes there can be no spaces:
```html
<p title=About W3Schools>
```
- Use single quotes when attribute contains double quotes:
```html
<p title='John "ShotGun" Nelson'>
```
- Use double quotes when attribute contains single quotes:
```html
<p title="John 'ShotGun' Nelson">
```

## HTML Attribute reference:
https://www.w3schools.com/tags/ref_attributes.asp