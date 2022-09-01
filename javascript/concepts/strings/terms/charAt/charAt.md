---
Title: '.charAt()'
Description: 'Returns a single character at the specified index of a string.'
Subjects:
  - 'Web Development'
  - 'Computer Science'
Tags:
  - 'Strings'
  - 'Methods'
CatalogContent:
  - 'introduction-to-javascript'
  - 'paths/front-end-engineer-career-path'
---

Returns a single character at the specified index of a string.

## Syntax

```js
string.charAt(index);
```

`index` is a required parameter representing the index of the character you want to return.

## Examples

Find the first character in a string:

```js
const greeting = 'Hello World';

const firstLetter = greeting.charAt(0);

console.log(firstLetter);
// Output: H
```

Find the last character in a string:

```js
const greeting = 'Hello World';

const lastLetter = greeting.charAt(greeting.length - 1);

console.log(lastLetter);
// Output: d
```
