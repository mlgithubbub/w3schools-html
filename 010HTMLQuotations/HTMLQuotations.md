# HTML Quotation and Citation Elements

## HTML `<blockquote>` for Quotations

- `<blockquote>` element defines a section quoted from another source
- browsers typically indent `<blockquote>` elements

```html
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>
```

## HTML `<q>` for Short Quotations

- `<q>` tag defines a short quotation
- browsers normal insert quotation marks around the quotation

```html
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```

## HTML `<abbr>` for Abbreviations

- `<abbr>` tag defines an abbreviation or an acronym like "HTML", "CSS", "Mr.", "Dr.", "ASAP", etc.
- gives useful info to browsers, translation systems and search engines

```html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

## HTML `<address>` for Contact Information

- `<address>` tag defiens contact info for author/owner of a document/article
- can be email address, URL, physical address, phone number, etc.
- usually renders in italic
- browsers always ass a line break before and after the address element

```html
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```

## HTML `<cite>` for Work Title

- `<cite>` tag defines title of creative work (book, movie, poem, song, etc.)
- usually renders in italic

```html
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
```

## HTML `<bdo>` for Bi-Directional Override

- `<bdo>` tag overrides current text direction

```html
<bdo dir="rtl">This text will be written from right to left</bdo>
```

