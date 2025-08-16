# HTML Media & Anchor Tags 

This project demonstrates **HTML media elements** (image, audio, video) and **anchor (link) tags** along with their attributes. It is part of the **WebDev Series Day 03**.

---

---

## 📖 Overview
This HTML file shows how to embed and control **images, videos, and audio** in a webpage, and how to create **internal and external hyperlinks** using the anchor `<a>` tag. All important attributes are included for better learning.

---

## 🖼️ Image Tag `<img>`

### Syntax
```html
<img src="image.jpg" alt="Description" width="400" height="300">
````

### Attributes

| Attribute | Description                             | Example                           |
| --------- | --------------------------------------- | --------------------------------- |
| `src`     | Path to the image file                  | `src="images/picture.jpg"`        |
| `alt`     | Alternative text if image fails to load | `alt="A scenic view"`             |
| `width`   | Width of the image in pixels            | `width="400"`                     |
| `height`  | Height of the image in pixels           | `height="300"`                    |
| `title`   | Tooltip text when hovered               | `title="Scenic View"`             |
| `loading` | Lazy loading (`lazy` or `eager`)        | `loading="lazy"`                  |
| `style`   | Inline CSS styling                      | `style="border:2px solid black;"` |

### Example

```html
<img src="images/pic.jpg" alt="Beautiful Landscape" width="400" height="300" title="Landscape">
```

---

## 🎬 Video Tag `<video>`

### Syntax

```html
<video src="video.mp4" controls autoplay loop muted width="640" height="360">
  Your browser does not support the video tag.
</video>
```

### Attributes

| Attribute          | Description                         | Example                    |
| ------------------ | ----------------------------------- | -------------------------- |
| `src`              | Path to the video file              | `src="videos/movie.mp4"`   |
| `controls`         | Show playback controls              | `controls`                 |
| `autoplay`         | Video starts automatically          | `autoplay`                 |
| `loop`             | Video repeats after ending          | `loop`                     |
| `muted`            | Mutes audio                         | `muted`                    |
| `width` / `height` | Video size                          | `width="640" height="360"` |
| `poster`           | Image to display before video plays | `poster="thumbnail.jpg"`   |

### Example

```html
<video src="videos/demo.mp4" controls autoplay muted loop width="640" height="360"></video>
```

---

## 🎵 Audio Tag `<audio>`

### Syntax

```html
<audio src="audio.mp3" controls autoplay loop></audio>
```

### Attributes

| Attribute  | Description                | Example                |
| ---------- | -------------------------- | ---------------------- |
| `src`      | Path to the audio file     | `src="audio/song.mp3"` |
| `controls` | Show playback controls     | `controls`             |
| `autoplay` | Play automatically on load | `autoplay`             |
| `loop`     | Repeat audio               | `loop`                 |
| `muted`    | Start audio muted          | `muted`                |

### Example

```html
<audio src="audio/music.mp3" controls autoplay loop></audio>
```

---

## 🔗 Anchor Tag `<a>`

### Syntax

```html
<a href="https://example.com" target="_blank" rel="noopener noreferrer" title="Example Link">Click Here</a>
```

### Attributes

| Attribute      | Description                                | Example                     |
| -------------- | ------------------------------------------ | --------------------------- |
| `href`         | URL or path to link                        | `href="https://google.com"` |
| `target`       | Where to open the link (`_blank`, `_self`) | `target="_blank"`           |
| `rel`          | Relationship for security                  | `rel="noopener noreferrer"` |
| `title`        | Tooltip text on hover                      | `title="Go to Google"`      |
| `download`     | Download file instead of opening           | `download="file.pdf"`       |
| `id` / `class` | Styling and JS targeting                   | `class="btn-link"`          |

### Examples

* External link (new tab):

```html
<a href="https://www.google.com" target="_blank" rel="noopener noreferrer">Visit Google</a>
```

* Internal link (same page / section):

```html
<a href="#section2">Go to Section 2</a>
```

* Download link:

```html
<a href="files/sample.pdf" download>Download PDF</a>
```

---

## 🌐 Live Preview

Click the link to **open the Day03 HTML file** in your browser:
[View Day03 Media & Anchor Tags](HTML/WebDev-Series-Day03/Day03HTML_Media&AnchorTag.html)

---

## ✅ Learning Outcomes

* Learn to embed and control **images, videos, and audio** in HTML.
* Understand all **important attributes** of `<img>`, `<video>`, `<audio>`, and `<a>` tags.
* Learn the difference between **internal and external links**.
* Create download links and tooltips using anchor attributes.
* Combine media with links for interactive web pages.

```
