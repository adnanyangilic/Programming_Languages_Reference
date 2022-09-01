---
Title: 'background-clip'
Description: 'Defines the boundary within the element box at which the background is no longer drawn.'
Subjects:
  - 'Web Development'
  - 'Web Design'
Tags:
  - 'Background'
  - 'Box Model'
CatalogContent:
  - 'learn-css'
  - 'paths/front-end-engineer-career-path'
  - 'paths/full-stack-engineer-career-path'
---

Defines the boundary within the element box at which the background is no longer drawn.

## Syntax

```css
background-clip: <value>;
```

Where `<value>` can be the following: `border-box` | `content-box` | `padding-box` | `text` | `initial`

## Example 1

Set background to the edge of the content box:

```css
body {
  background: #000000;
  border: 3px dashed blue;
  padding: 20px;
  background-clip: content-box;
}
```

## Example 2

Set background to the inside edge of the border:

```css
body {
  background: #000000;
  border: 3px dashed blue;
  padding: 20px;
  background-clip: padding-box;
}
```

## Example 3

Set background to the edge of the border:

```css
body {
  background: #000000;
  border: 3px dashed blue;
  padding: 20px;
  background-clip: border-box;
}
```

## Example 4

Set background within the foreground text:

```css
body {
  background: #000000;
  background-clip: text;
  color: transparent;
}
```
