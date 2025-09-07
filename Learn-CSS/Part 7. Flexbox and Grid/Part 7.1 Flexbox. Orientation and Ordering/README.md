# Flexbox and Grid

> Flexbox - items are aligned on a single axis. It is often described as being one-dimensional.

> Grid layouts are thought of as two-dimensional, because it can arrange items into rows and columns at the same time.

| Flexbox | Grid |
|---|---|
| Distribution across a single axis | Layouts with both rows and columns |

---

## Flexbox

* **flex container:** the parent element
* **flex items:** the child elements

```
<section class="flex-container">
    <div>flex item
        <div>not a flex item</div>
    </div>
    <div>flex item</div>
    <div>flex item</div>
    <div>flex item</div>
</section>
```

<img src="image1.png" width="400">

---

<img src="image2.png" width="600">

* The direction of the main axis can be changed to run vertically using the *flex direction* property.

```
<div class="container">
    <div>flex item</div>
    <div>flex item</div>
    <div>flex item</div>
    <div>flex item</div>
</div>
```

```
.container {
    display: flex;
    /* OR */
    display: inline-flex;
}
```

<img src="image3.png" width="600">
<img src="image4.png" width="600">

---

### flex-direction

> flex-direction - determines the direction of the main axis
>
> There are four values: *row, row-reverse, column and column-reverse.*

| Property | Image |
|---|---|
| flex-direction: row | <img src="image5.png" width="600"> |
| flex-direction: row-reverse | <img src="image7.png" width="600"> |
| flex-direction: column | <img src="image6.png" width="600"> |
| flex-direction: column-reverse | <img src="image11.png" width="600"> |
| flex-wrap: nowrap | <img src="image10.png" width="600"> |
| flex-wrap: wrap | <img src="image12.png" width="600"> |
| flex-wrap: wrap-reverse | <img src="image13.png" width="600"> |

---

#### flex-flow Shorthand

```
/* shorthand */
flex-flow: column wrap;

/* longhand */
flex-direction: column;
flex-wrap: wrap;
```
