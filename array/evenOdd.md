# Is The Number Even Or Odd?

Create a function that takes a number as an argument and returns "even" for even numbers and "odd" for odd numbers.

## Rules

* Input will always be whole numbers (don't worry about decimals).
* Negative whole numbers are fine.

## Examples

```javaScript
3 => "odd"
146 => "even"
19 => "odd"
```

Solution

```javaScript
function isEvenOrOdd(num) {
	return num % 2 === 0? 'even': 'odd'
}
```
