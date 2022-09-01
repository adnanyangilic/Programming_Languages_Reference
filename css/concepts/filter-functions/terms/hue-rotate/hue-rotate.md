---
Title: 'hue-rotate()'
Description: 'Accepts an angle value and rotates the hue of an element.'
Subjects:
  - 'Web Development'
  - 'Web Design'
Tags:
  - 'Images'
  - 'Functions'
  - 'Colors'
CatalogContent:
  - 'learn-css'
  - 'paths/front-end-engineer-career-path'
  - 'paths/full-stack-engineer-career-path'
---

Accepts an angle value and rotates the hue of an element.

## Syntax

```css
filter: hue-rotate(<angle>);
```

where a required `<angle>` can be one of the following: `.25turn`, `-45deg`, `1.57rad`, `31.3grad`

**Note:** Positive values increase the hue, negative values decrease the hue. A default value of `0` results in no change.

## Example 1

Rotate the hue of the image by 45 degrees:

```css
.banner-image {
  filter: hue-rotate(45deg);
}
```
