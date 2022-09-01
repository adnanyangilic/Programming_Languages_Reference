---
Title: 'Arrays'
Description: 'An array is a variable that can hold more than one value. Arrays in PHP are stored as value pairs that in other languages would be called a dictionary or a hashtable. Keys can be strings or integers. There are several methods of declaring an array in PHP. The array() function can be used, either with key-value pairs, or with values alone. Single brackets, [...] can also be used in place of the array() keyword. If any key value is omitted, the key will be found by incrementing the largest prior integer key. If a key is repeated, the new value will overwrite the prior key. php  "one", "item 2" => "two", "item 3" => "three", ); echo $array1["item 1"], ";", $array1["item 2"], ";", $array1["item 3"];'
Subjects:
  - 'Web Development'
  - 'Computer Science'
Tags:
  - 'Arrays'
  - 'Data Types'
CatalogContent:
  - 'learn-php'
  - 'paths/front-end-engineer-career-path'
  - 'paths/computer-science'
---

An array is a variable that can hold more than one value. Arrays in PHP are stored as value pairs that in other languages would be called a dictionary or a hashtable. Keys can be strings or integers.

## Syntax

There are several methods of declaring an array in PHP. The `array()` function can be used, either with key-value pairs, or with values alone. Single brackets, `[...]` can also be used in place of the `array()` keyword. If any key value is omitted, the key will be found by incrementing the largest prior integer key. If a key is repeated, the new value will overwrite the prior key.

```php
<?php
// The last comma can be omitted
$array1 = array( "item 1" => "one", "item 2" => "two", "item 3" => "three", );

echo $array1["item 1"], ";", $array1["item 2"], ";", $array1["item 3"];
// Output: one;two;three

$array2 = array("one", "two", "three");

echo $array2[0], ";", $array2[1], ";", $array2[2];
// Output: one;two;three

$array3 = ["one", 5 => "two", "three"];

echo $array3[0], ";", $array3[5], ";", $array3[6];
// Output: one;two;three

$array4 = [5 => "one", 5.7 => "two", "5" => "three"];

echo $array4[5];
// Output: three
?>
```

Additionally, when defining an array, the following key casts will occur:

- Strings containing valid `int` types, unless preceded by a `+` sign, will be cast to an `int` type key.
  As in the above example `"5"` is treated as `5`.
- `float` types will be cast to `int` types, truncating the fractional part.
  As in the above example `5.7` is treated as `5`.
- `bool` types are cast to `int` types. `true` is stored as `1` and `false` stored as `0`.
- `null` will be cast as the empty string, `""`.
- Arrays and objects cannot be used as keys and will result in an error: `Illegal offset type`.
