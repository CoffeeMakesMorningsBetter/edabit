# Find The Biggest And Smallest Numbers

Ben has a very simple idea to make some profit: he buys something and sells it again. Of course, this wouldn't give him any profit at all if he was simply to buy and sell it at the same price. Instead, he's going to buy it for the lowest possible price and sell it at the highest.

## Rules

* Return both the minimum and maximum number for the given array.

## Example

```javaScript
minMax([1,2,3,4,5])   == [1,5]
minMax([2334454,5])   == [5, 2334454]
minMax([1]) == [1, 1]
```

## Solution

```javaScript
function min(arr){
  var min = arr[0];
  for(var i = 1; i < arr.length; i++){
    if(min > arr[i]){
      min = arr[i]
    }
  }
  return min
}

function max(arr){
  var max = arr[0];
  for(var i = 1; i < arr.length; i++){
    if(max < arr[i]){
      max = arr[i]
    }
  }
  return max
}

function minMax(arr) {
   var x = min(arr)
   var y = max(arr)
   return [x, y]
}

minMax([1,2,3,4])
```
