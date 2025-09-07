# Inheritance and Specificity

## Inheritance

> CSS styles can be inherited from the ancestor to descendant elements.

Apply base styles to the body selector.

```
body {
    color: #222222;
}
```

```
h1 {
    color: #222222;
}
h2 {
    color: #222222;
}
p {
    color: #222222;
}
```

> Some elements **CAN NOT** be *inherited*

---

## Specificity

> Specificity determines how browsers decide which CSS rule takes precedence.

in CSS file:

```
p {
    color: red;
}
.example {
    color: blue;
}
```

in HTML file:

```
<p class="example">Red or Blue?</p>
```

> Each one overrides the previous one

    !from lowest to highest

    1. universal (*)
    2. type (p)
    3. class (.example)
    4. id (#example)

> The *double type* will override the *single type*

```
p {
    color: green;       <-- not this one
}

section p {
    color: lightgreen;  <-- will be this one
}
```

### Specification Calculation

    A. Count the number of ID selectors.
    B. Count the number of class, attribute, and pseudo-class selectors.
    C. Count the number of type and pseudo-element selectors.
    The universal selector has a value of 0.

```
*           a=0     b=0     c=0     =   000
p           a=0     b=0     c=1     =   001
.class      a=0     b=1     c=0     =   010
#id         a=0     b=0     c=0     =   100
.class p    a=0     b=1     c=1     =   011
#id p       a=0     b=0     c=0     =   101
ul li a     a=0     b=0     c=3     =   003
```
