# Return The Objects Keys And Values

Create a function that takes an object and returns the keys and values as separate arrays.

## Example

```javaScript
{a: 1, b: 2, c: 3} => [["a", "b", "c"], [1, 2, 3]]
{a: "Apple", b: "Microsoft", c: "Google"} => [["a", "b", "c"], ["Apple", "Microsoft", "Google"]]
{key1: true, key2: false, key3: undefined} => [["key1", "key2", "key3"], [true, false, undefined]]
```

## Solution
```javaScript
function keysAndValues(obj) {
  var key = []
  var values = []
  for(var prop in obj){
    key.push(prop)
    values.push(obj[prop])
  }
  return [key, values]
}
```
