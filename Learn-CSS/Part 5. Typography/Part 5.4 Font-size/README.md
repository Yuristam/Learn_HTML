# font-size


#### font-size: px, em, rem

* Different units for specifying the font size

* Relative values are calculated based on the nearest ancestor element

* Absolute values are fixed and not affected by ancestor elements

#### font-size: px

* Screens are measured in pixels

* Absolute value, great for accuracy

* Use whole numbers, avoid decimals

* Browser default = 16px

#### font-size: em

* Named after the letter "m"

* Relative unit

* Can use whole numbers or decimal points

* 1em = inherited font-size

#### font-size: rem

* root em

* Relative unit

* Only relative to the root element (<html>)

* Not affected by parent or ancestor elements

---

### Font Shorthand Property

* font-style

* font-size

* font-weight

* font-family

* font-variant

* line-height

#### longhand vs. shorthand

```
/* shorthand */
font: italic small-caps bold 24px/1.5 Helvetica, sans-serif;
```

```
/* longhand */
font-style: italic;
font-variant: small-caps;
font-weight: bold;
font-size: 24px;
line-height: 1.5;
font-family: Helvetica, sans-serif;
```

---

### Font Shorthand Syntax Rules

* Must include values for the font-size and font-family

`font: italic small-caps bold 24px/1.5 Helvetica, sans-serif;`

* May optionally include values for font-style, font-variant, font-weight, and line-height

`font: italic small-caps bold 24px/1.5 Helvetica, sans-serif;`

* Order matters! font-style, font-variant, and font-weight must precede font-size

* font-variant = normal or small-caps only

* font-size/line-height

* font-family must be the last value specified

`font: italic small-caps bold 24px/1.5 Helvetica, sans-serif;`
