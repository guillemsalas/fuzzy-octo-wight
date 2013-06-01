#F.js
### Compressed future/promise snippet

#####Get a new future instance:
var f = F();
#####Subscribe to promise
f.on.ok(successHandler).ko(errorHandler);
#####Trigger the future
######error
f.ko(data);
######success
f.ok(data);