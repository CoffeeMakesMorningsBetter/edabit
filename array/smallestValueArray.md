# Find The Smallest Number

Create a function that takes an array of numbers and returns the smallest number in the set.

## Example

```javaScript
[34, 15, 88, 2] => 2
[34, -345, -1, 100] => -345
[-76, 1.345, 1, 0] => -76
[0.4356, 0.8795, 0.5435, -0.9999] => -0.9999
[7, 7, 7] => 7
```

## Test Cases

* Test cases contain positive and negative numbers.
* Test cases contain decimals.

## Solution

```javaScript
function findSmallestNum(arr){
  var small = arr[0];
  for(var i = 0; i < arr.length; i++){
    if(small >  arr[i]){
      console.log(small)
      small = arr[i]
    }
  }
  return small
}


function findSmallestNum(arr) {
  arr.sort(function(a,b){
    return a - b
  })
  return arr.shift()
}
```
