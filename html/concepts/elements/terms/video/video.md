---
Title: '<video>'
Description: 'Represents an interface for adding video content to the page.'
Subjects:
  - 'Web Development'
  - 'Web Design'
Tags:
  - 'Elements'
  - 'Tags'
  - 'Video'
CatalogContent:
  - 'learn-html'
  - 'paths/front-end-engineer-career-path'
---

The **`<video>`** element represents an interface for adding video content to the page.

## Syntax

```html
<!-- Surrounding source tag -->
<video>
  <source src="filename.mp4" type="video/mp4" />
  <h3>Fallback text if video will not play</h3>
</video>

<!-- With src attribute -->
<video src="filename.mp4">
  <h3>Fallback text if video will not play</h3>
</video>
```

The `<video>` element may include [`<source>`](https://www.codecademy.com/resources/docs/html/elements/source) elements and fallback text. It may also use attributes to convey intention. Some common ones are below:

- `autoplay`: If this attribute is present the video will play automatically.
- `controls`: If this attribute is present the video will have an overlay allowing the user to control the video.
- `height` and `width`: Control the height and width dimensions of the video element (in pixels).
- `poster`: The URL for a photo to show the user while the video is loading.
- `src`: The URL for the video that should be shown to the user.

## Examples

The following example shows the `<video>` element being used with embedded `<source>` element:

```html
<html>
  <head> </head>
  <body>
    <video controls height="480" poster="code_ninja.jpg">
      <source type="video/webm" src="code_ninja.webm" />

      Sorry you can't watch this video in your browser. Click
      <a href="code_ninja.webm">here</a> to download it, instead.
    </video>
  </body>
</html>
```

<video controls style="width: 100%;" crossorigin="anonymous">
  <source src="https://raw.githubusercontent.com/Codecademy/docs/main/media/html-video-tag-example.mp4" type="video/mp4" />
  <track default kind="captions" srclang="en" src="https://raw.githubusercontent.com/Codecademy/docs/main/media/html-video-tag-example.vtt" />
</video>
