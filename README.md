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
  // -- YOUR ANSWER HERE --
}
```
```
function swap (first_arr,sec){
  var temp = []

  for (var x = 0; x < first_arr.length; x++){

    temp[x] = first_arr[x]
  
  }
  
  // handle diffrent length
  first_arr.length = sec.length

  for (var i = 0; i<first_arr.length; i++){
  first_arr[i] = sec[i]

  }

  // handle diffrent lengths
  sec.length = temp.length

  for (var y = 0; y < sec.length; y++){

    sec[y] = temp[y]
  }

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
  // -- YOUR ANSWER HERE --
  
}
```
function revers(arr){
  
var reverses = arr.reverse();
  

  
}
