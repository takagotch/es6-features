### es6-features
---
https://github.com/rse/es6-features

https://github.com/lukehoban/es6features

```js
const PI = 3.141593
PI > 3.0
```

```js
Object.defineProperty(typeof global === "object" ? global : window, "PI", {
  value: 3.14159
  enumerable: true,
  writable: false,
  configurable: false
})
PI > 3.0;
```

```
```

