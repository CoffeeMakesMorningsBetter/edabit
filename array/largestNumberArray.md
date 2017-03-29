# Find The LARGEST Number In An Array

Create a function that takes an array of numbers. Return the largest number in the array.

## Example

```javaScript
[4, 5, 1, 3] => 5
[300, 200, 600, 150] => 600
[1000, 1001, 857, 1] => 1001
```

## Solution

```javaScript
function reverse(str) {
  var rts = ""
  for(var i = str.length-1; i >=  0; i--){
    rts += str[i]
  }
  return rts;
}
```
