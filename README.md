# Oh hi there!

## There is a feature I would have wanted to have in Lodash, but there was none.

## This was the for..in loop (and the normal for loop)

## The raw code is around 100 bytes (not accounting for README.md and package.json), so no bloat!

## Example code:
```
const loops = require("forloops")
let arr = [1,3,4,9];
loops.forin(arr,e => {
    console.log(e,arr[e]);
    // Returns index and element
})
loops.repeat(3, e => {
    console.log(e);
    // Returns 0, 1, 2
})
```
