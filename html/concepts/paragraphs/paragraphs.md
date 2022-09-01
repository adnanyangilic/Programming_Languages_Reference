---
Title: 'Paragraphs'
Description: 'Paragraphs are block-level elements that contain and display a block of text. They are enclosed by an opening and closing tag.'
Subjects:
  - 'Web Development'
  - 'Web Design'
Tags:
  - 'Paragraph'
CatalogContent:
  - 'learn-html'
  - 'paths/front-end-engineer-career-path'
---

Paragraph element `<p>` contains and displays a block of text. They are among the most common text-based HTML elements.

They are block-level, which means it is as wide as it's parent element and as tall as its content's height.

## Syntax

The pargraph element is enclosed by an opening `<p>` tag and a closing `</p>` tag:

```html
<p>
  This is a block of text! Lorem ipsum dolor sit amet, consectetur adipisicing
  elit.
</p>
```

## Example

```html
<!DOCTYPE html>
<html>
  <body>
    <div style="width: 50%; margin: auto; border: 2px solid black;">
      <p style="padding: 10px; font-family: system-ui;">
        It was love at first sight. The first time Yossarian saw the chaplain he
        fell madly in love with him. Yossarian was in the hospital with a pain
        in his liver that fell just short of being jaundice.
      </p>
    </div>
  </body>
</html>
```

![Paragraph example](https://raw.githubusercontent.com/Codecademy/docs/main/media/html-paragraph-example.png)

## Accessibility with Paragraphs

Paragraphs are relatively easy for accessibility devices, such as screen readers, to find and process. The more `<p>` elements, the better.
