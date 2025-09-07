# HTML File

## The HTML Page

> **HTML file** - the first file that's returned in response to a request for a webpage.

> **The *Doctype* Declaration** - Declares which era this HTML file is from
> **The *head* Element** - Contains information the browser needs to know, though it won't be displayed on the page
> **The *body* Element** - Contains the information and content that will be displayed on the page


```
<!doctype html>
<html lang="en-US" dir="ltr">
    <head>
        ...
    </head>
    <body>
        ...
    </body>
</html>
```

---

##### The *meta* element

- Only used inside the head
- Conveys metadata about the page

```
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="description" content="A description of this site that will show up in search engine results.">
```

```
<meta name="application-name" content="Filament Group">
<meta name="msapplication-TitleImage" content="/images/icons/mstile-144x144.png">
<meta name="theme-color" content="#247200">
<link rel="manifest" href="/webappmanifest.json">
```

---

> **The *link* Element** - Links to a range of other assets we want to load
> **The *rel* Attribute** - Tells the browser which kind of asset it is
> **The *href* Attribute** - Provides the URL to the asset

`<link href="main.css" rel="stylesheet">`

`<link rel="icon" href="favicon.ico">`

`<link rel="preload" href="myFont.woff2" as="font" type="font/woff2" crossorigin="anonymous">`

---

> **The *script* Element** - Tells the browser to load a JavaScript file

`<script src="my-javascript-file.js"></script>`

---

## HTML Structure

- main
- header
- footer
- article
- section
- aside

> **The *main* Element** - Wraps around the main content of the page
> **The *header* and *footer* Elements** - Used to mark places on the page where the content is a header or a footer
> **The *article* Element** - Wrapped around any instance of an article

>*Tweet* or *social media post*, a *teaser card* can be marked up as an ***article*** element

> **The *section* Element** - Wraps around sections of content
> **The *aside* Element** - Marks content that is off to the side or not the main attraction

```
<body>
    <main>
        ...
    </main>
</body>
```