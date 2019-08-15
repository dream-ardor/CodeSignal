## Given an array of strings, return another array containing all of its longest strings.
```js
Example
For inputArray = ["aba", "aa", "ad", "vcd", "aba"], the output should be
allLongestStrings(inputArray) = ["aba", "vcd", "aba"].
```
### :coffee: My Code
```js
const allLongestStrings = arr => 
arr.sort((a,b)=> b.length - a.length)
    .filter(x => x.length == arr[0].length);
```
