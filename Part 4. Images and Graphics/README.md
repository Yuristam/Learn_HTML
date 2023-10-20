# Images and Graphics

## Images

> **&lt;img&gt;** - you can add images to your page using this tag
> **src=""** - the path of the image
> **alt=""** - this is alternate text for an image, if the image cannot be displayed. The alt attribute provides alternative information for an image if a user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).
> **width=""** **height=""** - size of the image

`<img src="image.jpg">`
`<img src="image.jpg" alt="black dog" width="400px" height="300px">`

> **src** can be *absolute* or *relative*

---

### Image Formats

1) **GIF**
2) **SVG** (Scalable vector graphic)
3) **JPG** or **JPEG** (Image format for compressing photos)
4) **PNG**

> ##### GIF
>
> - Does well compressing large areas of a single color
> - Limited color space of 256 colors
> - Can do transparency, with jagged edges
> - Can have multiple frames, and make a little movie

> ##### SVG
>
> - Logos, icons, etc.
> - Vector file

> ##### JPG
>
> - Can be compressed
> - Size vs. quality

> ##### PNG
>
> - Images that need transparency
> - Good at compression
> - Photos and images
> - Depends on the use case

---

### Image in Header

```
<header>
    <img src="image.png"
    width="300px" height="400px"
    alt="image">
    <h1>Header Headline Title</h1>
</header>
```

---

### Responsive Images

> **srcset=""** - allows you to specify multiple files to be used based on either viewport width or image pixel width

```
<img src="image.jpg"
     alt="dog with glasses"
     width="400px" height="300px" 
     srcset="image.jpg 2x,
    	        image.jpg 3x,
	        image.jpg 4x">
```

---

### Responsive Width

> **sizes=""** - Lists which size image to use at which media query

```
<img src="image.jpg"
     alt="dog with glasses"
     width="400px" height="300px" 
     srcset="image.jpg 2x,
    	        image.jpg 3x,
	        image.jpg 4x" 
     sizes="(max-width: 480px) 240px,
            (max-width: 960px) 480px,
            (max-width: 1440px) 960px,
            1920px">
```

---

### Responsive Pictures

> **&lt;picture&gt;** - Allows you to define different images for different browser window sizes.
> **&lt;source&gt;** - The path of the different image

```
<picture>
     <source media="(min-width:600px)"
             srcset="image-720.jpg">
     <source srcset="image-cropped-320.jpg">

     <img src="image.jpg"
          width="400px" height="300px"
          alt="dog with glasses">
</picture>
```

```
<picture>
     <source media="(min-width:600px)"
             srcset="image-320.jpg 320w,
                     image-480.jpg 480w,
                     image-720.jpg 720w,
                     image-960.jpg 960w,
                     image-1440.jpg 1440w,
                     image-1920.jpg 1920w" >
     <source srcset="image-cropped-320.jpg 320w,
                     image-cropped-480.jpg 480w,
                     image-cropped-720.jpg 720w,
                     image-cropped-960.jpg 960w">

     <img src="image-480.jpg"
          alt="dog with glasses"
          height="360px" width="480px">
</picture>
```

---

### Figure and Figcaption

> **&lt;figure&gt;** - For anything that appears as a figure, illustrating something
> **&lt;figcaption&gt;** - For demonstration of a concept which needs a caption

```
<figure>
     <img src="image.jpg" width="960" height="720" alt="dog with sunglasses">

     <figcaption>Chilling dog with sunglasses.</figcaption>
</figure>
```