# Return The Four Letter Strings

Create a function that takes an array of strings. Return all words in the array that are exactly four letters.

## Example

```javaScript
"Ryan", "Kieran", "Jason", "Matt"] => ["Ryan", "Matt"]
["Tomato", "Potato", "Pair"] => ["Pair"]
["Kangaroo", "Bear", "Fox"] => ["Bear"]
```

## Solution

```javaScript
function isFourLetters(arr) {
  var isFour = []
  for(var i = 0; i < arr.length; i++){
    if(arr[i].length === 4){
      isFour.push(arr[i])
    }
  }
  return isFour
}
```
