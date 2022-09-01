---
Title: 'Strings'
Description: 'Strings are a primitive data type. They are any grouping of characters (letters, spaces, numbers, or symbols) surrounded by single quotes or double quotes.'
Subjects:
  - 'Web Development'
  - 'Computer Science'
Tags:
  - 'Strings'
  - 'Methods'
  - 'Data Types'
CatalogContent:
  - 'introduction-to-javascript'
  - 'paths/create-a-back-end-app-with-javascript'
---

**Strings** are a primitive data type. They are any grouping of characters (letters, spaces, numbers, or symbols) surrounded by single quotes `'` or double quotes `"`.

## Concatenation

In JavaScript, multiple strings can be concatenated or joined together using the `+` [operator](https://www.codecademy.com/resources/docs/javascript/operators).

In the example below, multiple strings and variables containing string values have been concatenated. After the code block is run, the `displayText` variable will contain the concatenated string:

```js
let service = 'credit card';
let month = 'May 30th';
let displayText = 'Your ' + service + ' bill is due on ' + month + '.';

console.log(displayText);
// Output: Your credit card bill is due on May 30th.
```

## Interpolation

String interpolation is the process of evaluating string literals containing one or more placeholders (expressions, variables, etc). It can be performed using template literals (`text ${expression} text`), as in the following example:

```js
let age = 7;

// String concatenation
'Tommy is ' + age + ' years old.';

// String interpolation
`Tommy is ${age} years old.`;
```
