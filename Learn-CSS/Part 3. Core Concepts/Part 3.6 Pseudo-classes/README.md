# Pseudo-classes and links

in HTML file:

```
<a>no href</a>
<a href="#">:link</a>
<a href="#">:visited</a>
<a href="#">:hover</a>
<a href="#">:active</a>
<a href="#">:focus</a>
```

in CSS file:

```
body {
    font-size: 20px;
}
a {
    color: red;
}
a:link {
    color: green;
}
a:visited {
    color: gray;
}
a:focus {
    outline: 1px solid black;
}
a:hover {
    background: gray;
}
a:active {
    color: white;
}
```

> **Pseudo classes:** *:link, :visited, :focus, :hover, :active*

> **hover** - activates when you put your *mouse cursor*
> **active** - activates when you *click* on it
> **link** - is a link (that has *href* value)
> **visited** - is a link that was *visited*
> **focus** - activates when you use *tab* key
