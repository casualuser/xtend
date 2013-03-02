# xtend

Extend like a boss

xtend is a basic utility library which allows you to extend an object by appending all of the properties from each object in a list. When there are identical properties, the right-most property takes presedence.

## Examples

```js
var extend = require("xtend")

var combination = extend({
    a: "a"
}, {
    b: "b"
})
// { a: "a", b: "b" }
```


## MIT Licenced
