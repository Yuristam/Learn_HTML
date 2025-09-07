# Values in CSS

### Shorthand and Longhand Properties

```
/* longhand */
padding-top: 10px;
padding-right: 5px;
padding-bottom: 10px;
padding-left: 5px;
```

```
/* shorthand */
padding: 10px 5px;
```

---

## Values and Units

```
/* valid */
color: red;
color: rgb(255,0,0);
font-size: 10px;
font-size: 1rem;
```

```
/* not valid */
color: 10px;
font-size: red;
```

### Numeric Values

```
width: 80%;
height: 10em;
border-width: 5px;
animation-iteration-count: 5;
```

```
font-weight: 400;
font-size: 1.25rem;
```

```
transform: rotate(360deg);
animation-duration: 750ms;
```

---

### Length

> The ***length*** data type is used to specify sizing with two types of units: absolute and relative.

#### Absolute *length*

- Fixed unit, always the same size
- Not affected by values in related elements
- Example: px, cm, mm, pt

#### Relative *length*

- Relational sizing, not fixed
- Dependent upon values declared in parent and ancestor elements
- Example: em, rem, vw, vh

---

### Unitless Values

> Some numeric values do not require a unit

```
line-height: 1.25;
```

```
margin: 0px 2px;
/* same as */
margin: 0 2px;
```

- Keywords do not require a unit

```
color: red;
font-size: medium;
font-weight: bold;
```

---

### CSS Function Values

> The syntax always includes the function name and parenthesis

```
/* Rotate an element */
transform: rotate();

/* Calculate a computed value */
width: calc();

/* Embed an image to the background of an element */
background-image: url();
```

```
/* Rotate an element */
transform: rotate(90deg);

/* Calculate a computed value */
width: calc(80% - 20%);

/* Embed an image to the background of an element */
background-image: url('myimage.png');
```

---

### Initial Value

- Default browser styles

```
/* initial value */
h1 {
    font-weight: bold;
}
```
