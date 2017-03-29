# Remove All Duplicates From An Array

Create a function that accepts an array as an argument. Remove all duplicate items from the array and return the new array.

## Rules

* Remove duplicate items from array.
* New array should be sequentially the same as old array, minus duplicate items.

## Gotchas

* Test cases contain arrays with both strings and numbers.
* Is case sensitive.

## Example

```javaScript
["John", "Taylor", "John"] => ["John", "Taylor"]
[1, 0, 1, 0] => [1, 0]
['The', 'big', 'cat'] => ['The', 'big', 'cat']
```

## Solution

```javaScript
function removeDups(arr) {
  var duplicateFree = []
  for(var i = 0; i < arr.length; i++){
    if(duplicateFree.indexOf(arr[i]) === -1){
      duplicateFree.push(arr[i]);
    }
  }
  return duplicateFree
}
```
