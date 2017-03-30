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
function findlargestNum(arr){
  var big = arr[0];
  for(var i = 0; i < arr.length; i++){
    if(big < arr[i]){
      console.log(small)
      big = arr[i]
    }
  }
  return big
}
```
