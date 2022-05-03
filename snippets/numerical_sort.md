---
title: Numerical_Sort
tags: array
expertise: intermediate
firstSeen: 2022-05-03T05:00:00-04:00
---

Explain briefly what the snippet does.

- Sorts the numbers in ascending and descending orders.
- Use Array.prototype.sort() to sort the given array
- For numerical sorting, a Comparator entity or compare function has to be created. For ascending it returns a - b and for descending it returns b - a.

```js
const asc_sort = (...nums) => nums.sort(function(a, b)
  {return a - b; });

const des_sort = (...nums) => nums.sort(function(a, b)
  {return b - a; });
```

```js
asc_sort(20, 100, 80, 50); // (20, 50, 80, 100)
des_sort(20, 100, 80, 50); // (100, 80, 50, 20)
```
