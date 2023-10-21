# Media

## Audio

> **&lt;audio&gt;** - element is used to place audio
> **src=""** - the path of the audio

`<audio src="audio.mp3"></audio>`

> **src** can be *absolute* or *relative*

> **controls** - shows buttons for the audio (to play, pause, etc.) 
> **loop** - for loop
> **autoplay** - for autoplay

`<audio controls src="audio.mp3"></audio>`

`<audio src="audio.mp3" loop autoplay></audio>`

---

### Audio Formats

1) **OGG**
2) **MP3**

```
<audio>
    <source src="audio.ogg" type="audio/ogg">
    <source src="audio.mp3" type="audio/mpeg">
</audio>
```

```
<audio controls loop autoplay>
    <source src="audio.ogg"
            type="audio/ogg; codec=opus">
    <source src="audio.mp3"
            type="audio/mpeg">

    Sorry your browser doesn't support this audio.
</audio>
```

---

## Video

> **&lt;video&gt;** - element is used to place video
> **src=""** - the path of the video

`<video src="video.mp4"></video>`

> **src** can be *absolute* or *relative*

> **controls** - shows buttons for the video (to play, pause, etc.) 
> **loop** - for loop
> **autoplay** - for autoplay
> **muted** - for mute

> **width** and **height** - are for size

#### Video Properties

- 720x480
- h.264
- .mp4

> The *H.264* codec currently has the widest support across browsers.

```
<video controls>
    <source src="video.webm"
            type="video/webm">
    <source src="video.mp4"
            type="video/mp4">
</video>
```

---

## Captions and Subtitles

> **&lt;track&gt;** - element is used to put subtitles
> **src=""** - the path of the subtitles

```
<video controls>
    <source src="video.webm"
            type="video/webm">
    <source src="video.mp4"
            type="video/mp4">
    
    <track src="subtitles.vtt"
           kind="captions"
           label="English"
           srclang="en"
           default>

    <track src="subtitles.es.vtt"
           kind="subtitles"
           label="Espanol"
           srclang="es">

    <track src="description.en.vtt"
           kind="descriptions"
           label="Descriptions"
           srclang="en">

    <p>This would be a video of a city, if your device supported playing this video.</p>
</video>
```

> **kind** - type of captions
> **label** - label for language of subtitle
> **srclang** - language of the subtitles
> **default** - subtitle chosen by default

> **src** can be *absolute* or *relative*

---

## Embedded Media

> **&lt;iframe&gt;** - element is used to put embedded media

```
<iframe width="600" height="315" 
        src="https://www.youtube.com/embed/gYO1uk7vIcc?si=cEsfaP-xoAxjNkG6" 
        frameborder="0" 
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
</iframe>
```

> You can use this from many website, such as YouTube, Spotify, etc.