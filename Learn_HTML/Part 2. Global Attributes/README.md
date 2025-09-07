# Attributes

## Global Attributes

> **Global Attributes** - attributes that can be applied to any HTML element

#### In HTML there are the 4 most important attributes:

1) **class** - allows us to target all elements with that class in our CSS and JS

```
<p class="intro">
    This is the introduction.
</p>
```

2) **id** - allows us to target a unique element with that id in our CSS and JS

```
<p class="intro" id="article-intro">
    This is the introduction.
</p>
```

> **id** and **class** are used to edit elements in *CSS* and *JS*

3) **lang** - language of the page

```
<p lang="en-GB">This paragraph is in British English.</p>

<p lang="de">Dieser Absatz ist auf Deutsch.</p>
```

4) **dir** - direction of text [LTR= left to right; RTL = right to left; auto]

```
<p dir="ltr">This paragraph is in English. It flows from left to right.</p>

<p dir="rtl">هذه الفقرة باللغة العربية. يتدفق من اليمين إلى اليسار.</p>
```

---

### Another Global Attributes

- **contenteditable** - allows to edit the content

```
<blockquote contenteditable="true">
    Edit this content to add your own quote.
</blockquote>

<cite contenteditable="true">Your name here</cite>
```

---

### ARIA Roles

> **ARIA Roles** HTML attributes that provide accessible information about that specific element

---

### Encoded Characters

#### Entity - Character
`&lt;` - <
`&gt;` - >
`&amp;` - &
`&copy;` - &copy;
`&trade;` - &trade;
`&star;` - &star;

> `&nbsp;` - the space that will never break

```
<p>Attack on Titan's main character is Eren&nbsp;Yeager</p>
```
