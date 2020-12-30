# Oh hi there!

## There is a feature I would have wanted to have in Lodash, but there was none.

## This was the for..in loop (and the normal for loop)

## The raw code is 150 bytes (not accounting for README.md and package.json), so no bloat
## I program in functional programming most of the time but sometimes my mind thinks in an imperative style, so that's why I made this
## Example code

```javascript
const loops = require("forloops")
let arr = [1,3,4,9];
loops.forin(arr,e => {
    console.log(e,arr[e]);
    // Returns index and element
})
loops.repeat(arr.length, e => {
    console.log(e);
    // Returns 0, 1, 2, 3
})
// Reverse the order
loops.repeat(arr.length,true, e => {
    console.log(e)
    // Returns 3, 2, 1, 0
})
```
