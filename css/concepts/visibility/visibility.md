---
Title: 'Visibility'
Description: 'The visibility property shows or hides an element. If the element is hidden, it will still take up space within the page. css visibility: ;  The visibility property has three values. - visible: Shows the element. - hidden: Hides the element.'
Subjects:
  - 'Web Development'
  - 'Web Design'
Tags:
  - 'Visibility'
  - 'Tables'
CatalogContent:
  - 'learn-css'
  - 'paths/front-end-engineer-career-path'
  - 'paths/full-stack-engineer-career-path'
---

The visibility property shows or hides an element. If the element is hidden, it will still take up space within the page.

## Syntax

```css
visibility: <value>;
```

The visibility property has three values.

- `visible`: Shows the element.
- `hidden`: Hides the element.
- `collapse`: Hides both the element and the space it would have occupied.

**Note:** `collapse` should only be used with `<table>` rows, row groups, columns, and column groups. If `collapse` is used on other elements, it will be treated the same as `hidden`. Implementing collapse within a `<table>` can be especially useful because it allows for hiding rows or columns without affecting the table layout.

## Example 1

Hiding an element with an `id` of `hide`.

```css
.hide {
  visibility: hidden;
}
```

## Example 2

Hiding a `<tr>` element within a table.

```css
tr {
  visibility: collapse;
}
```
