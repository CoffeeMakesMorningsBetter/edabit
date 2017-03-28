# Check If String Ending Matches Second String

Create a function that takes a two strings and returns true if the first argument ends with the 2nd argument (also a string).

## Rules

* Take two strings as arguments.
* Determine if second string matches ending of first string.
* Return boolean value.

Examples

```JavaScript
"abc", "bc" => true
"abc", "d" => false
"samurai", "zi" => false
"feminine", "nine" => true
"convention", "tio" => false
```

Solution

```JavaScript
function checkEnding(str1, str2) {
  // find the str2 length
  	// use the length of str2 to slice a substring of str1
  		// compare the substring and str1
  return str1.slice(-(str2.length)) === str2
}
```
