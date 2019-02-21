# F.js

> Compressed future/promise snippet

## Quick usage guide:
```js

var f = F();

# subscribe to the promise
f.on.ok(successHandler).ko(errorHandler);

# trigger failure
f.ko(data)

# trigger success
f.ok(data)

```
