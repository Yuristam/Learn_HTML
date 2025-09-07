# Web Fonts with @font-face

* Downloaded font files
* Included in your project files just like other files (i.e. images)
* Declare and link to font files using @font-face

### @font-face

```
@font-face {
    font-family: "My Font";
    src: url(my-font.woff); /* relative path */
    src: url(http://example.com/fonts/my-font.woff); /* absolute path */
}
```

```
body {
    font-family: "My Font", Helvetica, sans-serif;
}
```

---

### url()

```
/* valid */
src: url(my-font.woff);
src: url("my-font.woff");
src: url('my-font.woff');
src: url("my font.woff");
src: url(my\font.woff);
```

```
/* not valid */
src: url(my font.woff);
```

---

### Cross-Browser Compatibility

```
@font-face {
    font-family: 'MyWebFont';
    src: url('webfont.eot'); /* IE9 Compat Modes */
    src: url('webfont.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
        url('webfont.woff2') format('woff2'), /* Super Modern Browsers */
        url('webfont.woff') format('woff'), /* Pretty Modern Browsers */
        url('webfont.ttf') format('truetype'), /* Safari, Android, iOS */
        url('webfont.svg#svgFontName') format('svg'), /* Legacy iOS */        
}
```
