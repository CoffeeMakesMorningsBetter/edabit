# Return The Middle Character(s) In A String

Create a function that takes a string and returns the middle character(s). If the word's length is odd, return the middle character. If the word's length is even, return the middle two characters.

## Examples

```javaScript
"test" => "es"
"testing" => "t"
"middle" => "dd"
"A" => "A"
```

## Solution

```javaScript
function getMiddle(str) {
  return str.length % 2 !== 0 ? str.slice(Math.floor(str.length/2),Math.floor(str.length/2)+1): str.slice(str.length/2-1, str.length/2 + 1)
}
```
