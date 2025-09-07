# The Cascade and Importance

### Cascade

> The cascade in Cascading Style Sheets refer to how style rules are applied based on specificity and source order.

- Style declarations *cascade* and are read from top to bottom

```
p {
    font-size: 12px;
}

/* This style will take precedence */
p {
    font-size: 16px;
}

p {
    color: black;
    padding: 20px;
    font-size: 12px;
    font-size: 16px; /* This style will take precedence */
}

/* This style will take precedence - it has a higher specificity value */
.example {
    font-size: 16px;
}
p {
    font-size: 12px;
}
```

```
<p class="example">Paragraph</p>
```

### Importance

> The **!important** keyword overrides source order and specificity

```
p {
    font-size: 12px!important; /* This style will take precedence */
}
.example {
    font-size: 16px;
}
```

> The only way to override a style declaration with important is to use a selector

```
p {
    font-size: 12px!important;
}
p.class {
    font-size: 18px!important; /* This style will take precedence */
}
```
