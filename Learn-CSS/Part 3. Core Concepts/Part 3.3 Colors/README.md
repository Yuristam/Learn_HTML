# Colors in CSS

#### Basic Color Keywords

- red
- blue
- green
- black

#### Extended Color Keywords

- mediumseagreen
- oldlace
- aliceblue
- blanchedalmond

---

### Hexadecimal

- Prefixed with a number sign (**#**) followed by six characters (*0-9 and A-F*)
- Defines the *red*, *green*, and *blue* values: **#rrggbb**

```
#000000 /* black */
#ffffff /* white */
#ffa500 /* orange */
#ffc0cb /* pink */
#808080 /* grey */
```

- The notation is case-insensitive

```
/* all the same */
color: #ffffff;
color: #FFFFFF;
color: #FFFfff;
```

#### Hexadecimal Shorthand and Longhand

- The hex value can be abbreviated if the RGB values are the same

```
#rgb = #rrggbb

#f00; /* shorthand */
#ff0000; /* longhand */

#000; /* shorthand */
#000000; /* longhand */
```

---

### RGB

- **RGB** values define colors according to its red, green, and blue components

#### rgb()

- 3 comma-separated numbers between 0-255 or 0%-100%

```
rgb(0, 0, 0) /* black */
rgb(0%, 0%, 0%) /* black */

rgb(255, 255, 255) /* white */
rgb(100%, 100%, 100%) /* white */

/* spaces are not required */
rgb(255, 127, 80)
rgb(255,127,80)
```

#### rgb() and rgba()

- Use rgba() and a fourth value to change the opacity

```
rgb(0, 0, 0)        /* no alpha channel */
rgba(0, 0, 0, 0)    /* 0% opacity */
rgba(0, 0, 0, 0.5;) /* 50% opacity */
rgba(0, 0, 0, 1)    /* 100% opacity */
```

---

## Color Options

- RGB values match to keywords
- More color options with RGB values

```
color: red;
color: #FF0000;
color: rgb(255,0,0);
```

```
color: lime;
color: #00FF00;
color: rgb(0,255,0);
```

```
color: blue;
color: #0000FF;
color: rgb(0,0,255);
```

---

### HSL

- Defines the color value by its hue, saturation, and lightness
- Also include an optional alpha component

####  hsl() and hsla()

```
/* hue, saturation, lightness, alpha/opacity */
hsl(270, 60%, 70%)
hsla(270, 60%, 70%, 0.7)
```

#### hsl() Hue

- The hue is specified as an angle
- The value can be declared with or without the degree unit

```
hsl(*270*, 60%, 70%)
hsl(*270deg*, 60%, 70%)
```

#### hsl() Saturation

- Saturation is represented with a percentage
- 100% is full saturation, 0% is gray

```
hsl(270, *60%*, 70%)
hsl(270deg, *60%*, 70%)
```

#### hsl() Lightness

- Lightness is represented as a percentage
- 100% = white, 0% = black, 50% = normal

```
hsl(270, 60%, *70%*)
hsl(270deg, 60%, *70%*)
```

#### hsla() Alpha Channel

- The alpha channel can be represented as a decimal or percentage

```
hsla(270, 60%, 50%, *.15*)
hsla(270, 60%, 50%, *15%*)
```
