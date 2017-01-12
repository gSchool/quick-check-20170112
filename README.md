# Quick Check

For this pop quiz, feel free to use your editor/repl.it to write your answer.
Paste your answer into the appropriate place below when you are done.

## Standard: Solve problems that require swapping

### Write a function that swaps two arrays

e.g.
```js
var first_arr = [1, 2, 3]
var second_array = [4, 5, 6]

swap(first_arr, second_array)

console.log(first_arr) // [4, 5, 6]
console.log(second_array) // [1, 2, 3]
```

```js
function swap(arr1, arr2) {
  let one = arr1;
  let two = arr2;
  arr1 = two;
  arr2 = one;
}
```

### Write a function that reverses an array in place, using ONLY the swap function that you wrote above

e.g.
```js
var third_array = [3, 8, 4]

console.log(third_array) // [3, 8, 4]
reverse(third_array)
console.log(third_array) // [4, 8, 3]
```

```js
function reverse(array) {
  let regular = array;
  let opposite = [];
  for (let i = array.length-1; i > -1; i--) {
    opposite.push(array[i]);
  }
  swap(regular, opposite)
  return regular;
}
```
