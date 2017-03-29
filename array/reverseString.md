# Reverse The Order Of A String

Create a function that takes a string as its argument and returns the string in reversed order.

## Example

```javaScript
"Hello World" => "dlroW olleH"
"The quick brown fox." => ".xof nworb kciuq ehT"
"Edabit is really helpful!" => "!lufpleh yllaer si tibadE"
```
## Solution

```javaScript
function reverse(str) {
  var rts = ""
  for(var i = str.length-1; i >= 0; i--){
    rts += str[i]
  }
  return rts;
}
```
