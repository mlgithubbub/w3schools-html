# HTML Colors

- are specified with:
    - color names
    - RGB
    - HEX
    - HSL
    - RGBA
    - HSLA... values

## Color Names

- Tomato, Orange, etc.
- HTML supports 140 standard color names: https://www.w3schools.com/colors/colors_names.asp

## Background Color

- you can set the background color for elements:

```html
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
```

## Text Color

- you can set the color of text:

```html
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
```

## Border Color

- you can set the color of borders:

```html
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>
```

## Color Values

- colors can also be specified using RGB, HEX, HSL, RGBA, and HSLA values
- RGBA and HSLA values add an alpha channel to the colors

```html
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
```

# HTML RGB and RGBA Colors

- RGB colors have red, green and blue light sources
- RGBA colors have red, green and blue light sources + 1 alpha channel: opacity

## RGB Color Values

- in HTML RGB values are specified using this formula

```html
rgb (red, green, blue)
```

- each parameter defines the intensity of the color from 0 to 255
- there are 256 x 256 x 256 = 16777216 possible colors

Examples:
```html
<!-- This is red -->
rgb(255,0,0)
<!-- This is green -->
rgb(0,255,0)
<!-- This is blue -->
rgb(0,0,255)
<!-- Thus is black -->
rgb(0,0,0)
<!-- This is white -->
rgb(255,255,255)
```

## Shades of Gray

- shades of gray are often define using equal values for all three parameters:

```html
<!-- Gray 1 -->
rgb(60,60,60)
<!-- Gray 2 -->
rgb(100,100,100)
```

## RGBA Color Values

```html
rgba(red, green, blue, alpha)
```

- the alpha parameter is a number between 0.0 (fully transparent) and 1.0 (fully opaque)

# HTML HEX Colors

- hexadecimal colors are specified like:
```html
#rrggbb
```
- rr (red), gg (green), bb (blue) are hexadecimal values between 00 and ff (same as 0-255)

```html
<!-- This is red -->
#ff0000
<!-- This is green -->
#00ff00
<!-- This is blue -->
#0000ff
```

## Shades of Gray

- shades of gray are often made using three equal values of red, green and blue:

```html
<!-- Gray 1 -->
#404040
<!-- Gray 2 -->
#bebebe
```

# HTML HSL and HSLA Colors

- HSL stands for hue, saturation and lightness
- HSLA adds an alpha channel (transparency/opacity)

## HSL Color Values

- HSL colors are specified like:
```html
hsl (hue, saturation, lightness)
```
- hue = degree on the color wheel from 0 - 360
- saturation = intensity of a color = shade of gray from 0% (completely gray) to 100% (full color)
- lightness = lightness of a color = from 0% (black) to 100% (white)

## Shades of Gray

- set hue and saturation to 0, and adjust lightness from 0-100% to get darker/lighter shades

## HSLA Color Values

- specified with:

```html
hsla(hue, saturation, lightness, alpha)
```

- alpha is a number between 0.0 (fully transparent) and 1.0 (fully opaque)

