# HTML Links

- links allow users to click their way from page to page
- links are found on nearly all web pages

## HTML Links - Hyperlinks

- HTML links are hyperlinks
- click on a link to jump to another document
- when you mouse over a link, the mouse arrow turns to a little hand
- NOTE: Links do not have to be text, they can also be an image or any other HTML element

## HTML Links- Syntax

- HTML tag `<a>` defines a hyperlink and has this syntax:

```html
<a href="url">link text</a>
```

- `href` is the most important attribute because it indicates the link's destination
- the *link text* is the part visible to the user

Example:
```html
<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>
```

By default, in browsers:
- an unvisited link: underlined + blue
- a visited link: underlined + purple
- active link: underline + red
- but they can be styled with CSS to have a different look

## HTML Links - The target Attribute

- by default, linked page is displayed in current browser window
- specify another link for the target to change this
- `target` attribute specifies where to open the linked document
- `target` can have one of the following values:
    - `_self`: default, opens the document in the same tab/window it was clicked
    - `_blank`: opens document in a new tab/window
    - `_parent`: opens document in the parent frame
    - `_top`: opens document in the full body of the window

Example:
```html
<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>

```

## Absolute URLs vs. Relative URLs

- `absolute URL`: full web address
- `relative URL`: a local link, a link to a page within the same website

Example:
```html
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>
```

## HTML Links - Use an Image as a Link

- put the `<img>` tag inside the `<a>` tag:

```html
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
```

## Link to an Email Address

- use `mailto:` inside the `href` attribute to create a link that open's the user's email program:

```html
<a href="mailto:someone@example.com">Send email</a>

```

## Button as a Link

- you must add some JavaScript code
- JavaScript allows you to specify what happens at certain events such as the click of a button

```html
<button onclick="document.location='default.asp'">HTML Tutorial</button>
```

## Link Titles

- `title` attribute specifies extra info about an element
- info is most often shown as a tooltip text

```html
<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>
```

## More on Absolute URLs and Relative URLs

- use a full URL to link to a web page:
```html
<a href="https://www.w3schools.com/html/default.asp">HTML tutorial</a>
```

- link to a page in html folder on current web site:
```html
<a href="/html/default.asp">HTML tutorial</a>
```

- link to a page located in same folder as the current page
```html
<a href="default.asp">HTML tutorial</a>
```

## HTML Links - Different Colors

- HTML links are shown in different colors depending on whether `visited`, `unvisited` or `active`

### HTML Link Colors

- default:
    - `unvisited`: underlined + blue
    - `visited`: underlined + purple
    - `active`: underlined + red

You can change link state colors using CSS:
```html
<style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>
```

### Link Buttons

- links can also be styled as buttons using CSS:
```html
<style>
a:link, a:visited {
  background-color: #f44336;
  color: white;
  padding: 15px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: red;
}
</style>
```

## HTML Links - Create Bookmarks

- HTML links can be used to create `bookmarks`
- `bookmarks` let users jump to specific parts of a web page

### Create a Bookmark in HTML

- `bookmarks` can be useful if a web page is very long
- first create a bookmark, then add a link to it
- when link is clicked, page will scroll up or down to bookmark location

Example:
1. Use `id` attribute to create a bookmark:
```html
<h2 id="C4">Chapter 4</h2>
```
2. add a link to the bookmark:
```html
<a href="#C4">Jump to Chapter 4</a>
```

You can also add a link to a bookmark on another page:
```html
<a href="html_demo.html#C4">Jump to Chapter 4</a>

```



