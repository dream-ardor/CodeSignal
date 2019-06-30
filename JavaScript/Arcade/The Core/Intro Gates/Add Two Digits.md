## Add Two Digits
You are given a two-digit integer n. Return the sum of its digits.

Example
```js
For n = 29, the output should be
addTwoDigits(n) = 11.
```
###  My Code :full_moon_with_face:
```js
const addTwoDigits = n => n.toString().split('').map(Number).reduce((a,b)=>a+b);
```
