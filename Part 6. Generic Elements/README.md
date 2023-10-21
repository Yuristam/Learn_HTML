# General

## Supporting languages

> **charset** -this attribute defines the alphabet or set of characters for the script language

`<meta charset="UTF-8">`

> If in your website there are several languages you can use **lang** attribute for different parts

```
<p lang="ru">
    Хе́льсинки (фин. <span lang="fi">Helsinki</span>, швед. <span lang="sv">Helsingfors</span>) — столица Финляндии.
</p>
```

> **Unicode** - A universal encoding standard for characters encompassing many languages

---

## Div and Span

> **&lt;div&gt;** - is an *block-line level container* used to mark up a part of a text, or a part of a document.
> **&lt;span&gt;** - is an *inline container* used to mark up a part of a text, or a part of a document.

```
<article lang="en">
    <h1>This is headline</h1>
    <div class="box">
    <p>The first paragraph.</p>
    <p>The second paragraph.</p>
    <p>Third paragraph. <span lang="ru" class="bilingual">Тут текст на другом языке.</span> Some of this text is in another language.</p>
    <p>The fourth paragraph.</p>
    </div>
</article>
```
