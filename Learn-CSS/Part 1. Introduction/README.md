# Introduction to CSS

## HTML vs CSS

##### HTML

- Structure of content
- Semantic meaning

##### CSS

- Appearance
- Styling

---

## Referencing CSS (External CSS vs Internal CSS)

> There are 2 ways to load the external CSS file into the HTML, with a ***link tag*** or using the ***@import*** method.

---

### External CSS

#### External CSS with `<link>`

- Always referenced within the *`<head>`* of the document

```
<head>
    <link rel="stylesheet" href="css/styles.css">
</head>
```

> **rel=""** - stands for the relationship and uses the value of stylesheet
> **href=""** - the path to the CSS file

---

#### External CSS using @import

##### In styles.css file 

```
@import url('/styles/layout.css');
@import url('/styles/typography.css');
@import url('/styles/buttons.css');
```

##### In index.html file

```
<head>
    <style> @import url("css/styles.css");</style>
</head>
```

---

### Inline CSS 

- use ***style=""***

`<p style="color: red;">Red paragraph.</p>`

```
<h1 style="color: green;">Heading</h1>
<p style="color: red; font-size: 12px; background: #000000;">paragraph</p>
<p style="text-transform: uppercase; color:blue;">another paragraph</p>
```

```
<head>
    <style>
        h1 {
            color: green;
        }
        h2 { 
            color: blue;
        }
    </style>
</head>
```
