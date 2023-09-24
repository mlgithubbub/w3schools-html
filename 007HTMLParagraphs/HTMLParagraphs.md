# HTML Paragraphs

- always stars on a new line
- is usually a block of text

### HTML Paragraphs

- `<p>` element defines a paragraph
- always starts on a new line
- browsers always automatically add some white space before and after a margin

### HTML Display

- different screens create different results
- you can't add extra spaces or lines to your html code
- the browser will automatically remove any extra spaces and lines when the page is displayed

```html
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>
```

### HTML Horizontal Rules

- `<hr>` defines a thematic break in an HTML page
- is most often displayed as a horizontal rule
- used to separate content or define a change in and HTML page
- is an *empty tag*, has no end tag
```html
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```

### HTML Line Breaks

- `<br>` defines a line break
- use if you want a new line without starting a new paragraph

```html
<p>This is<br>a paragraph<br>with line breaks.</p>
```

### The `<pre>` Element

This poem displays on a single line:
```html
<p>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</p>
```

- use `<pre>` element to define preformatted text
- text inside `<pre>` is displayed in a fixed-width font, usually Courier, and it preserves spaces and line breaks

```html
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```