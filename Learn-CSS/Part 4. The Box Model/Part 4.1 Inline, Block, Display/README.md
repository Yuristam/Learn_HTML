# Inline, Block, Display

### Inline 

* Takes up the same space as their content.
* Elements are displayed in a line, from the left 
* Elements will only wrap when items cannot fit
* `<a>`, `<span>`, `<strong>`

<img src="inline-elements.png" width="250">

### Block

* Same height as content, same width as container
* Always starts on a new line
* `<p>`, `<h1>`, `<article>`, `<section>`

<img src="block-elements.png" width="200">

### The Display Property 

    Used to change the default behavior of inline and block-level elements

```
p {
    background: greenyellow;
    display: inline; 
    padding: 20px;
}
span {
    background: lightblue;
    display: block;
    padding: 20px;
}
```

```
display: inline-block;
```

| Before | After | Inline-block |
|---|---|---|
| <img src="display-before.png" width="450"> | <img src="display-after.png" width="450"> | <img src="inline-block.png" width="450"> |
