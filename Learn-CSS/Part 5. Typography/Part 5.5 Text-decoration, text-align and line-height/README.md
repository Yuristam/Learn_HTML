# Text-decoration, text-align, and line-height

### text-decoration

```
text-decoration: none; /* removes underline */
```

```
/* shorthand */
text-decoration: underline red solid;
```

```
/* longhand */
text-decoration-line: underline;
text-decoration-color: red;
text-decoration-style: solid;
```

### text-align

> The **text-align** property can be used to align content *within* a block element
>
> Add it to the *HTML element* itself or *the parent element*

```
header {
    text-align: center;
    text-align: left;
    text-align: right;
    text-align: justify;
}
```

### line-height

> The **line-height** property sets the height of the space between two lines of text
>
> Closely related to font-size
>
> Can use different value types (px, %, ems, rems, or unitless)

```
p {
    font-size: 16px;
    line-height: 16px;
}
```

```
p {
    font-size: 16px;
    line-height: 1.5;
}
```

```
p {
    font-size: 16px;
    line-height: 150%;
}
```
