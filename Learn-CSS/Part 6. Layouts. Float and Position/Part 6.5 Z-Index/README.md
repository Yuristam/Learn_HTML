# Z-index

> The ***z-index*** property specifies the stack order of an element.

<img src="image1.png" width="400">

---

### Stacking order

* ***root elements** (html, body)*
* ***block-level elements** (in order that they appear in the HTML)*
* ***floated elements** (that are not positioned)*
* ***in-line elements** (in order that they appear in the HTML)*
* ***positioned elements** (in order that they appear in the HTML)*
* ***z-index** (the higher the value, the higher the element)*

> **Note:** *z-index* only works on positioned elements (position:absolute, position:relative, or position:fixed).

---

### Example

| Element | Example |
|---|---|
| *root element* | <img src="image2.png" width="300"> |
| *block-level element 1* | <img src="image3.png" width="300"> |
| *block-level element 2* | <img src="image4.png" width="300"> |
| *float* | <img src="image5.png" width="300"> |
| *in-line* | <img src="image6.png" width="300"> |
| *position* | <img src="image7.png" width="300"> |
| *z-index 1* | <img src="image8.png" width="300"> |
| *z-index 2* | <img src="image9.png" width="300"> |
