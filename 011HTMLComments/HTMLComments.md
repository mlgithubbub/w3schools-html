# HTML Comments

## HTML Comment Tag

```html
<!-- Write your comments here -->
```
- Not the exclamation point in the start tag, but not in the end tag

### Add Comments

- use comments to place notifications and reminders in your HTML code

```html
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->
```

### Hide Content

- use commentst to hide content temporarily

```html
<p>This is a paragraph.</p>

<!-- <p>This is another paragraph </p> -->

<p>This is a paragraph too.</p>
```

- you can also hide more than one line:

```html
<p>This is a paragraph.</p>
<!--
<p>Look at this cool image:</p>
<img border="0" src="pic_trulli.jpg" alt="Trulli">
-->
<p>This is a paragraph too.</p>
```

- comments are great for debugging HTML and searching for errors

### Hide Inline Content

- comments can also be used to hide parts in the middle of the HTML code:

```html
<p>This <!-- great text --> is a paragraph.</p>
```