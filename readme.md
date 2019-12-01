# What are `prototype` and `__proto__`?

the only true difference between `prototype` and `__proto__` is that the former is a property of a class constructor, while the latter is a property of a class instance.

```javascript
function foo() {}
const f = new foo();
console.log(foo.prototype === f.__proto__); //true
```
