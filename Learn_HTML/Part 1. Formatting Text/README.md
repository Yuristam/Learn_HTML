# Introduction to HTML

## Paragraphs, Headlines, Articles, Commentary

> **Comments in Html**
>
> `<!-- This is comment in Html -->`

### Paragraphs, headlines, articles

- `<p></p>` - paragraph
- `<h1></h1>` - headline (from 1 to 6)
- `<article></article>` - article

---

#### DOM (Document Object Model) Tree  

```
<article>
	<h1> this is headline</h1>
	<p>this is first paragraph</p>
	<p>this is second paragraph</p>
	<p>this is <em>third</em> paragraph</p>
</article>
```

---

## Italic and Bold

### Italics

`<i></i>` - generic italic
`<em></em>` - emphasized italic

### Bold

`<b></b>` - generic bold
`<strong></strong>` - bold (used for Importance, Warning, Urgency)

---

## Lists in Html

- ##### Unordered list
- ##### Ordered list
- ##### Definition list

`<ul></ul>` - Unordered list
`<ol></ol>` - Ordered list
`<li></li>` - list item

#### Unordered List

```
<ul>
	<li> Item1 </li>
	<li> Item2 </li>
	<li> Item3 </li>
	<li> Item4 </li>
</ul>
```

#### Ordered List

```
<ol>
	<li> Item1 </li>
	<li> Item2 </li>
	<li> Item3 </li>
	<li> Item4 </li>
</ol>
```

---

#### Definition List 

- `<dl></dl>` - definition list
- `<dt></dt>` - definition term
- `<dd></dd>` - definition description

```
<dl>
	<dt>term1</dt>
	<dd>description1</dd>
	<dt>term2</dt>
	<dd>description2</dd>
	<dt>term3</dt>
	<dd>description3</dd>
	<dt>term4</dt>
	<dd>description4</dd>
</dl>
```

---

## Quotes in Html

### Blockquote

- `<blockquote></blockquote>` - block quote (to add author, use `<cite>`)
- `<cite></cite>` - author's name in `<blockquote>` tag

```
<blockquote>
	<p>
        The journey of a thousand miles begins with one step.
	</p>
	<cite>Lao Tzu</cite>
</blockquote>
```

---

### Quotation Marks

`<q></q>` - quotation marks (it changes the marks with attribute [lang = ""])

```
<p lang="en">
    <q>
        Big journeys begin with small steps.
    </q>
</p>
```

---

## Time in Html

`<time></time>` - time tag

---

## Code tags in Html

### Code, Encodings

`<code></code>` - code tag

`&lt;` - (Encoding, shows "<" in Html page)
`&gt;` - (Encoding, shows ">" in Html page)

---

## Break lines, superscripts, subscripts, small text

- `<br>` - line break (moves text to the next line)
- `<pre></pre>` - shows everything in text just like in code, with all line-breaks

- `<sub></sub>` - subscript (e.g. H2O, 2 is subscript)
- `<sup></sup>` - superscript (e.g. 2^2, 2 in power of 2)
- `<small></small>` - small text
