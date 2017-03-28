# Return The Last Item In An Array

Create a function that accepts an array and returns the last item in the array. The array can contain any of JavaScript's five primitive data types.

1. Number
2. String
3. Boolean
4. Undefined
5. Null

Examples

```JavaScript
[true, false, true] => true
['cat', 'dog', 'duck'] => 'duck'
[1, 2, 3] => 3
```

Solution

```JavaScript
function getLastItem(arr) {
  return arr[arr.length-1]
}

function getLastItem(arr) {
  return arr.pop()
}
```
